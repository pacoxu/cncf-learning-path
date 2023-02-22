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
## The CNCF repos
| ID |    REPO     | STARS | UPDATEDAT  | CREATEDAT  | FORKSCOUNT |
|----|-------------|-------|------------|------------|------------|
|  1 | kubernetes  | 96032 | 2023-02-22 | 2014-06-06 |      35250 |
|  2 | prometheus  | 46836 | 2023-02-22 | 2012-11-24 |       7895 |
|  3 | etcd        | 42658 | 2023-02-22 | 2013-07-06 |       9076 |
|  4 | istio       | 32446 | 2023-02-22 | 2016-11-18 |       6991 |
|  5 | helm        | 23788 | 2023-02-22 | 2015-10-06 |       6560 |
|  6 | envoy       | 21482 | 2023-02-22 | 2016-08-08 |       4138 |
|  7 | harbor      | 19424 | 2023-02-22 | 2016-01-28 |       4275 |
|  8 | containerd  | 13239 | 2023-02-22 | 2015-11-13 |       2718 |
|  9 | coredns     | 10298 | 2023-02-22 | 2016-03-18 |       1847 |
| 10 | flannel     |  7782 | 2023-02-22 | 2014-07-10 |       2793 |
| 11 | velero      |  7057 | 2023-02-22 | 2017-08-02 |       1183 |
| 12 | serving     |  4874 | 2023-02-22 | 2018-01-24 |       1011 |
| 13 | cluster-api |  2740 | 2023-02-22 | 2018-03-07 |       1077 |



## Skipped repos
moby/moby
projectcalico/calico
opencontainers/runc
kubernetes/ingress-nginx
torvalds/linux
cilium/cilium<!--END_SECTION:github_repos-->
