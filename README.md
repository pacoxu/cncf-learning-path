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
| ID |     REPO      | STARS | UPDATEDAT  | CREATEDAT  | FORKSCOUNT |
|----|---------------|-------|------------|------------|------------|
|  1 | moby          | 65551 | 2023-03-24 | 2013-01-18 |      18574 |
|  2 | prometheus    | 47310 | 2023-03-24 | 2012-11-24 |       7994 |
|  3 | etcd          | 42958 | 2023-03-24 | 2013-07-06 |       9129 |
|  4 | istio         | 32649 | 2023-03-24 | 2016-11-18 |       7042 |
|  5 | envoy         | 21653 | 2023-03-24 | 2016-08-08 |       4181 |
|  6 | cilium        | 14759 | 2023-03-24 | 2015-12-16 |       2108 |
|  7 | ingress-nginx | 14617 | 2023-03-24 | 2016-11-04 |       7652 |
|  8 | containerd    | 13475 | 2023-03-24 | 2015-11-13 |       2771 |
|  9 | coredns       | 10424 | 2023-03-24 | 2016-03-18 |       1869 |
| 10 | runc          | 10116 | 2023-03-24 | 2015-06-05 |       1920 |
| 11 | flannel       |  7846 | 2023-03-24 | 2014-07-10 |       2812 |
| 12 | velero        |  7136 | 2023-03-24 | 2017-08-02 |       1197 |
| 13 | calico        |  4447 | 2023-03-24 | 2016-07-21 |       1050 |



## Skipped repos
goharbor/harbor
kubernetes/kubernetes
helm/helm
kubernetes-sigs/cluster-api
torvalds/linux
knative/serving<!--END_SECTION:github_repos-->
