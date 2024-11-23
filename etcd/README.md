# Commands

Manual set-up:

wget -q --https-only \
"https://github.com/coreos/etcd/releases/download/v3.3.9/etcd-v3.3.9-linux-amd64.tar.gz"

kubectl exec etcd-master –n kube-system etcdctl get / --prefix –keys-only (Run inside the etcdmaster POD)

etcd.service
--initial-cluster controller-0=https://${CONTROLLER0_IP}:2380,controller-1=https://${CONTROLLER1_IP}:2380 \\
