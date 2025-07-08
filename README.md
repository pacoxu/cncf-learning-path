# cncf-learning-path
record my learning CNCF related path in issues/pull requests

**archived: move to https://github.com/pacoxu/AI-Infra/**

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
| ID |                                                REPO                                                | STARS  | UPDATEDAT  | CREATEDAT  | FORKSCOUNT |                                                DESCRIPTIONS                                                |
|----|----------------------------------------------------------------------------------------------------|--------|------------|------------|------------|------------------------------------------------------------------------------------------------------------|
|  1 | [linux](https://github.com/torvalds/linux)                                                         | 196728 | 2025-07-01 | 2011-09-04 |      56765 | Linux kernel source tree                                                                                   |
|  2 | [kubernetes](https://github.com/kubernetes/kubernetes)                                             | 116064 | 2025-07-01 | 2014-06-06 |      40869 | Production-Grade Container Scheduling and Management                                                       |
|  3 | [moby](https://github.com/moby/moby)                                                               |  70011 | 2025-07-01 | 2013-01-18 |      18778 | The Moby Project - a collaborative project for the container ecosystem to assemble container-based systems |
|  4 | [vllm](https://github.com/vllm-project/vllm)                                                       |  51141 | 2025-07-01 | 2023-02-09 |       8434 | A high-throughput and memory-efficient inference and serving engine for LLMs                               |
|  5 | [etcd](https://github.com/etcd-io/etcd)                                                            |  49728 | 2025-07-01 | 2013-07-06 |      10099 | Distributed reliable key-value store for the most critical data of a distributed system                    |
|  6 | [containerd](https://github.com/containerd/containerd)                                             |  18889 | 2025-07-01 | 2015-11-13 |       3602 | An open and reliable container runtime                                                                     |
|  7 | [coredns](https://github.com/coredns/coredns)                                                      |  13121 | 2025-07-01 | 2016-03-18 |       2256 | CoreDNS is a DNS server that chains plugins                                                                |
|  8 | [runc](https://github.com/opencontainers/runc)                                                     |  12476 | 2025-07-01 | 2015-06-05 |       2193 | CLI tool for spawning and running containers according to the OCI specification                            |
|  9 | [kubeadm](https://github.com/kubernetes/kubeadm)                                                   |   3867 | 2025-07-01 | 2016-11-22 |        723 | Aggregator for issues filed against kubeadm                                                                |
| 10 | [cluster-api](https://github.com/kubernetes-sigs/cluster-api)                                      |   3860 | 2025-07-01 | 2018-03-07 |       1387 | Home for Cluster API, a subproject of sig-cluster-lifecycle                                                |
| 11 | [enhancements](https://github.com/kubernetes/enhancements)                                         |   3669 | 2025-07-01 | 2016-05-02 |       1547 | Enhancements tracking repo for Kubernetes                                                                  |
| 12 | [kwok](https://github.com/kubernetes-sigs/kwok)                                                    |   2858 | 2025-06-30 | 2022-07-28 |        225 | Kubernetes WithOut Kubelet -  Simulates thousands of Nodes and Clusters.                                   |
| 13 | [toc](https://github.com/cncf/toc)                                                                 |   1742 | 2025-07-01 | 2015-12-07 |        649 | ⚖️ The CNCF Technical Oversight Committee (TOC) is the technical governing body of the CNCF Foundation.    |
| 14 | [llmaz](https://github.com/InftyAI/llmaz)                                                          |    216 | 2025-06-30 | 2023-11-20 |         33 | ☸️ Easy, advanced inference platform for large language models on Kubernetes. 🌟 Star to support our work! |
| 15 | [system-validators](https://github.com/kubernetes/system-validators)                               |     38 | 2025-05-23 | 2019-08-20 |         28 | A set of system-oriented validators for kubeadm preflight checks.                                          |
| 16 | [cluster-api-provider-huawei](https://github.com/HuaweiCloudDeveloper/cluster-api-provider-huawei) |      7 | 2025-05-26 | 2024-12-23 |          7 | Kubernetes Cluster API Provider Huawei Cloud (CAPHW)                                                       |



#### Skipped repos
<!--END_SECTION:github_repos-->
