# Commands

Manual set-up:

wget -q --https-only "https://github.com/coreos/etcd/releases/download/v3.3.9/etcd-v3.3.9-linux-amd64.tar.gz"


## installing etcdctl command (like kubectl)
1. curl -L https://github.com/etcd-io/etcd/releases/download/v3.3.11/etcdv3.3.11-linux-amd64.tar.gz -o etcd-v3.3.11-linux-amd64.tar.gz
2. tar xzvf etcd-v3.3.11-linux-amd64.tar.gz
3. ./etcd

kubectl exec etcd-master –n kube-system etcdctl get / --prefix –keys-only (Run inside the etcdmaster POD)

etcd.service
--initial-cluster controller-0=https://${CONTROLLER0_IP}:2380,controller-1=https://${CONTROLLER1_IP}:2380 \\

# Default
kubectl get pods -n kube-system <br />
kubectl exec -it --namespace kube-system etcd-minikube sh <br />
docker exec -it minikube  /bin/bash
