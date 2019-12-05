Resources:

  - https://k3s.io/
  - https://rancher.com/blog/2019/2019-02-26-introducing-k3s-the-lightweight-kubernetes-distribution-built-for-the-edge/
  - https://rancher.com/blog/2019/2019-03-21-comparing-kubernetes-cni-providers-flannel-calico-canal-and-weave/
  - https://kubernetes.io/docs/reference/kubectl/cheatsheet/
  
Components:

  - CNI
    - https://github.com/coreos/flannel
    - https://github.com/projectcalico/calico
  - https://github.com/coredns/coredns
  - https://github.com/containous/traefik
  - https://istio.io/
  
  
Install k3s:

  - Download and install ubuntu VM
  - Take a snapshot
  - `curl -sfL https://get.k3s.io | sh -`
  
Install k3s from docker:
  - https://rancher.com/docs/k3s/latest/en/advanced/
  
Deploy web ui:
  - https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/

RBAC:
  - https://github.com/kubernetes/dashboard/blob/master/docs/user/access-control/creating-sample-user.md
  - https://kubernetes.io/docs/reference/access-authn-authz/authentication/