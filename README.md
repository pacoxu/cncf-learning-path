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
| ID |     REPO      | STARS  | UPDATEDAT  | CREATEDAT  | FORKSCOUNT |
|----|---------------|--------|------------|------------|------------|
|  1 | linux         | 144152 | 2023-01-10 | 2011-09-04 |      46202 |
|  2 | kubernetes    |  94994 | 2023-01-10 | 2014-06-06 |      34830 |
|  3 | prometheus    |  46268 | 2023-01-10 | 2012-11-24 |       7788 |
|  4 | etcd          |  42288 | 2023-01-10 | 2013-07-06 |       9009 |
|  5 | helm          |  23424 | 2023-01-10 | 2015-10-06 |       6510 |
|  6 | envoy         |  21204 | 2023-01-10 | 2016-08-08 |       4068 |
|  7 | harbor        |  19151 | 2023-01-10 | 2016-01-28 |       4246 |
|  8 | ingress-nginx |  14146 | 2023-01-10 | 2016-11-04 |       7390 |
|  9 | containerd    |  12922 | 2023-01-10 | 2015-11-13 |       2642 |
| 10 | coredns       |  10152 | 2023-01-10 | 2016-03-18 |       1825 |
| 11 | flannel       |   7688 | 2023-01-10 | 2014-07-10 |       2769 |



## Skipped repos
opencontainers/runc
vmware-tanzu/velero
knative/serving
kubernetes-sigs/cluster-api
istio/istio
moby/moby
projectcalico/calico
cilium/cilium<!--END_SECTION:github_repos-->
