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
| ID |  REPO  | STARS  | UPDATEDAT  | CREATEDAT  | FORKSCOUNT |
|----|--------|--------|------------|------------|------------|
|  1 | linux  | 145939 | 2023-02-10 | 2011-09-04 |      46661 |
|  2 | etcd   |  42532 | 2023-02-10 | 2013-07-06 |       9057 |
|  3 | envoy  |  21405 | 2023-02-10 | 2016-08-08 |       4117 |
|  4 | cilium |  14286 | 2023-02-10 | 2015-12-16 |       2033 |



## Skipped repos
kubernetes-sigs/cluster-api
goharbor/harbor
kubernetes/kubernetes
istio/istio
helm/helm
prometheus/prometheus
containerd/containerd
projectcalico/calico
kubernetes/ingress-nginx
vmware-tanzu/velero
knative/serving
moby/moby
coredns/coredns
opencontainers/runc
flannel-io/flannel<!--END_SECTION:github_repos-->
