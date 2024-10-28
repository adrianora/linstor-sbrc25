# linstor-sbrc25

## Deadlines

### Datas internas
- v0 do artigo: 01/11/2024
- v1 do artigo: 15/11/2024
- v2 do artigo: 29/11/2024

### [Simpósio Brasileiro de Redes de Computadores e Sistemas Distribuídos (SBRC)](https://sbrc.sbc.org.br/2025/pt_br/)
- Registro de artigos: 06/01/2025
- Submissão de artigos: 13/01/2025
- Comunicação de resultados: 13/03/2025
- Envio da versão final: 01/04/2025

## Linstor
- [Comparing LINSTOR & Ceph Storage Clusters](https://linbit.com/blog/how-does-linstor-compare-to-ceph/)
- [Comparing LINSTOR, Ceph, Mayastor, & Vitastor Storage Performance in Kubernetes](https://linbit.com/blog/comparing-linstor-ceph-mayastor-vitastor-storage-performance-in-kubernetes/)
- [What are the benefits of running DRBD in Diskless mode?](https://linbit.com/blog/what-are-the-benefits-of-running-drbd-in-diskless-mode/)
- [How LINSTOR Works](https://linbit.com/drbd-user-guide/linstor-guide-1_0-en/#_how_linstor_works)
- [LINSTOR Introduction & Demonstration](https://www.youtube.com/watch?v=-pwQ1Zzm1IE)
- [Exploring the World of DRBD: Distributed Replicated Block Devices](https://www.ktpql.com/distributed-replicated-block-devices/)
- [Issue: overprovisioning protections](https://github.com/LINBIT/linstor-server/issues/377)
- [Linstor Quickview: an in progress map of useful Linstor information](https://drive.google.com/file/d/12ohtcIUb6kirzCUJhsTTATeNUGnvV_sO/view?usp=sharing)
- [Linstor: networked storage without the complexity](https://brian-candler.medium.com/linstor-networked-storage-without-the-complexity-c3178960ce6b)
- [Linstor: concepts and configuration](https://brian-candler.medium.com/linstor-concepts-and-configuration-e5b0c8e10d27)



### papers
- [Linstor publications website index](https://linbit.com/drbd-user-guide/users-guide-drbd-8-4/#s-publications)
- [Lars Ellenberg. 'DRBD v8.0.x and beyond'. 2007](./papers/DRBD%208.0.x%20and%20beyond%20-%20Shared-Disk%20semantics%20on%20a%20Shared-Nothing%20Cluster.pdf)
- [Philipp Reisner. 'DRBD v8 – Replicated Storage with Shared Disk Semantics'](./papers/DRBD%20v8%20-%20Replicated%20Storage%20with%20Shared%20Disk%20Semantics.pdf)
- [Philipp Reisner. 'Rapid resynchronization for replicated storage'](./papers/Rapid%20resynchronization%20for%20replicated%20storage.pdf)

### Código
- [Swagger do Linstor](https://app.swaggerhub.com/apis-docs/Linstor/Linstor/1.19.0#/)

## Ceph
- [New in Luminous: Improved Scalability](https://ceph.com/community/new-luminous-scalability/)
    - In 2015, CERN ran a Ceph scalability experiment with 30 PB across 7200 OSDs
- [Ceph: A Journey to 1 TiB/s](https://ceph.io/en/news/blog/2024/ceph-a-journey-to-1tibps/)
- [Publications About Ceph](https://ceph.io/en/news/publications/)
- [Ceph Storage [A Complete Explanation]](https://www.lightbitslabs.com/blog/ceph-storage/)

### papers
- [Ceph publications website index](https://ceph.io/en/news/publications/)
- [Ceph: A Scalable, High-Performance Distributed File System](./papers/Ceph-%20A%20Scalable,%20High-Performance%20Distributed%20File%20System.pdf)
- [CRUSH: Controlled, Scalable, Decentralized Placement of Replicated Data](./papers/CRUSH%20-%20Controlled,%20Scalable,%20Decentralized%20Placement%20of%20Replicated%20Data.pdf)

## Digital Ocean
- [Why We Chose Ceph to Build Block Storage](https://www.digitalocean.com/blog/why-we-chose-ceph-to-build-block-storage)
- [How we Operate Ceph at Scale](https://ceph.com/assets/pdfs/events/2024/ceph-days-nyc/2024%20Ceph%20Day%20NYC%20How%20we%20Operate%20Ceph%20at%20Scale.pdf)
- [How we Operate Ceph at Scale | Ceph Days NYC 2024](https://www.youtube.com/watch?v=FmgZv_f8T8E)
- [Ceph Tech Talk: Ceph at DigitalOcean](https://www.youtube.com/watch?v=k_bTg72eOhU)
- [Digital Ocean Block Storage Performance](https://docs.digitalocean.com/products/volumes/details/features/)

# Oxide
- [Storage Architecture Considerations](https://rfd.shared.oxide.computer/rfd/60)
- [Implementation of Data Storage](https://rfd.shared.oxide.computer/rfd/0177)
- [Crucible Upstairs Refactoring](https://rfd.shared.oxide.computer/rfd/0444)
- [Crucible Upstairs Backpressure](https://rfd.shared.oxide.computer/rfd/0445)
- [Crucible: The Oxide Storage Service](https://oxide.computer/podcasts/oxide-and-friends/1734108)
- [Crucible: The Oxide Storage Service - Youtube](https://www.youtube.com/watch?v=UvEKSqBBcZw)
- [Crucible Code](https://github.com/oxidecomputer/crucible)

# Public Cloud storage performance
- [AWS](https://aws.amazon.com/pt/ebs/provisioned-iops/)
- [GCP](https://cloud.google.com/compute/docs/disks/performance#zonal_pd)
- [Azure](https://learn.microsoft.com/en-us/azure/virtual-machines/disks-types#disk-type-comparison)
- [AlibabaCloud](https://www.alibabacloud.com/help/en/ecs/user-guide/block-storage-performance#section-0hu-6dh-p6f)

## Dicas de escrita e leitura
- [Dicas para os Alunos de Mestrado do Prof. Jacques](http://www.dsc.ufcg.edu.br/~jacques/dicas.htm)
- [The Heilmeier Catechism](https://www.darpa.mil/work-with-us/heilmeier-catechism)

## Miscellaneous
- [Software Defined Storage with HPE Apollo and Ceph or Gluster](https://www.iistech.com/blog/software-defined-storage-with-hpe-apollo-and-ceph-or-gluster)
- [Observabilidade no Itaú - 100TB/dia de logs; maior cluster de Splunk LATAM](https://www.hipsters.tech/observabilidade-no-itau-hipsters-ponto-tech-334/)
- [How Banco Itaú tracks 1.5B daily metrics on-prem and in AWS with Grafana and observability](https://grafana.com/blog/2022/11/28/how-banco-itau-tracks-1.5b-daily-metrics-on-prem-and-in-aws-with-grafana-and-observability/)
- [RAID](https://en.wikipedia.org/wiki/RAID)
- [A Case for Redundant Arrays of Inexpensive Disks (RAID)](https://www.cs.cmu.edu/~garth/RAIDpaper/Patterson88.pdf)
- [PowerScale](https://www.dell.com/pt-br/shop/família-powerscale/sf/powerscale?hve=explore+powerscale)
- [PowerVault](https://www.dell.com/pt-br/shop/storage/sf/powervault?gacd=9687031-14004-5761040-273175705-0&dgc=ST&gad_source=1&gbraid=0AAAAACgzZXctUPk8vQ0fbPes4k-pcADj6&gclsrc=ds#compare-module)
- [What’s the Difference Between Block, Object, and File Storage?](https://aws.amazon.com/compare/the-difference-between-block-file-object-storage/)
