# How to install Linstor

Na documentação oficial tem um passo a passo de como instalar os componentes do Linstor, mas a coisa parece ser "corporativa" e mais fácil para quem é cliente da empresa. Em uma demo, o host mostra como instalar a partir do PPA do Linbit. O tutorial abaixo explica como subir um cluster em VMs usando o systemd, mas é possível usar containers.
### Preparar hosts
* O controle precisa ter a porta 3370 aberta (ou outra caso você altere).
* O nó satélite precisa ter a porta 3366 aberta (ou outra caso você altere).

Adicionar o PPA do Linbit em cada máquina
```bash
$ add-apt-repository ppa:linbit/linbit-drbd9-stack
$ apt update
$ apt install drbd-dkms drbd-utils linstor-controller linstor-satellite linstor-client -y
```
### Iniciar serviços e adicionar nodes
```bash
// No controller
$ systemctl enable –now linstor-controller
// No satélite
$ systemctl enable –now linstor-satellite
```

Para adicionar os nós aos cluster, execute os comandos no controller (repetir para cada um deles, se existir mais de 1)
```bash
$ linstor node create –node-type controller <node_name> <node_ip>
$ linstor node create –node-type satellite <node_name> <node_ip>
```

Para verificar se os nós foram adicionar com sucesso
```bash
$ linstor node list
```
