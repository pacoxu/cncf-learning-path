# cncf-learning-path
record my learning CNCF related path in issues/pull requests

## A simple summary
- Docker
- - Network: bridge 、 host、 overlay
- Registry
- Swarm
- - docker-compose
- - swarm service
- Swarmkit
- - cluster management; leader change: raft.
- Kubernetes 0.1
- - network: calico/flannel/macvlan; ingress/nodeport/F5
- - storage: scaleio/portworx
- - RBAC、RangeLimit、HPA、Prometheus、EFK
- Containerd
- Kubernetes 0.2
- - coredns
- - knative
- - kubeadm/kind
- - network: VLAN\istio\Keepalived VIP
- - velero、kubefed v2、VPA、Thanos
- Kubernetes 0.3
- - kubespray/kops
- - network cilium/submarinar/whereabouts; metallb
- - storage: hwameistor/local-storage
- - harbor/karmada
- - dex/pinniped
- - clusterpeida/merbridge
- - OpenTelementry

# CNCF repositories status
<!--START_SECTION:github_repos-->
### The DaoCloud open-source repos
| ID |                             REPO                              | STARS  | UPDATEDAT  | CREATEDAT  | FORKSCOUNT |                                                DESCRIPTIONS                                                |
|----|---------------------------------------------------------------|--------|------------|------------|------------|------------------------------------------------------------------------------------------------------------|
|  1 | [linux](https://github.com/torvalds/linux)                    | 194833 | 2025-06-03 | 2011-09-04 |      56090 | Linux kernel source tree                                                                                   |
|  2 | [kubernetes](https://github.com/kubernetes/kubernetes)        | 115481 | 2025-06-03 | 2014-06-06 |      40650 | Production-Grade Container Scheduling and Management                                                       |
|  3 | [moby](https://github.com/moby/moby)                          |  69820 | 2025-06-03 | 2013-01-18 |      18757 | The Moby Project - a collaborative project for the container ecosystem to assemble container-based systems |
|  4 | [prometheus](https://github.com/prometheus/prometheus)        |  58798 | 2025-06-03 | 2012-11-24 |       9570 | The Prometheus monitoring system and time series database.                                                 |
|  5 | [etcd](https://github.com/etcd-io/etcd)                       |  49512 | 2025-06-03 | 2013-07-06 |      10072 | Distributed reliable key-value store for the most critical data of a distributed system                    |
|  6 | [istio](https://github.com/istio/istio)                       |  36910 | 2025-06-02 | 2016-11-18 |       7975 | Connect, secure, control, and observe services.                                                            |
|  7 | [helm](https://github.com/helm/helm)                          |  27951 | 2025-06-03 | 2015-10-06 |       7252 | The Kubernetes Package Manager                                                                             |
|  8 | [envoy](https://github.com/envoyproxy/envoy)                  |  26040 | 2025-06-02 | 2016-08-08 |       4949 | Cloud-native high-performance edge/middle/service proxy                                                    |
|  9 | [harbor](https://github.com/goharbor/harbor)                  |  25664 | 2025-06-02 | 2016-01-28 |       4879 | An open source trusted cloud native registry project that stores, signs, and scans content.                |
| 10 | [cilium](https://github.com/cilium/cilium)                    |  21732 | 2025-06-03 | 2015-12-16 |       3225 | eBPF-based Networking, Security, and Observability                                                         |
| 11 | [containerd](https://github.com/containerd/containerd)        |  18668 | 2025-06-03 | 2015-11-13 |       3553 | An open and reliable container runtime                                                                     |
| 12 | [coredns](https://github.com/coredns/coredns)                 |  13020 | 2025-06-02 | 2016-03-18 |       2234 | CoreDNS is a DNS server that chains plugins                                                                |
| 13 | [runc](https://github.com/opencontainers/runc)                |  12395 | 2025-06-02 | 2015-06-05 |       2185 | CLI tool for spawning and running containers according to the OCI specification                            |
| 14 | [velero](https://github.com/vmware-tanzu/velero)              |   9223 | 2025-06-02 | 2017-08-02 |       1437 | Backup and migrate Kubernetes applications and their persistent volumes                                    |
| 15 | [calico](https://github.com/projectcalico/calico)             |   6490 | 2025-06-02 | 2016-07-21 |       1425 | Cloud native networking and network security                                                               |
| 16 | [kubeadm](https://github.com/kubernetes/kubeadm)              |   3854 | 2025-06-02 | 2016-11-22 |        722 | Aggregator for issues filed against kubeadm                                                                |
| 17 | [cluster-api](https://github.com/kubernetes-sigs/cluster-api) |   3824 | 2025-05-31 | 2018-03-07 |       1376 | Home for Cluster API, a subproject of sig-cluster-lifecycle                                                |
| 18 | [enhancements](https://github.com/kubernetes/enhancements)    |   3649 | 2025-06-02 | 2016-05-02 |       1534 | Enhancements tracking repo for Kubernetes                                                                  |
| 19 | [kwok](https://github.com/kubernetes-sigs/kwok)               |   2821 | 2025-06-02 | 2022-07-28 |        225 | Kubernetes WithOut Kubelet -  Simulates thousands of Nodes and Clusters.                                   |



#### Skipped repos
<!--END_SECTION:github_repos-->
