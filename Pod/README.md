# Commands

- kubectl run nginx --image=nginx <br />
- kubectl run nginx --image=nginx --dry-run=client -o yaml <br />
- kubectl get pod kube-XXX-XXXX -n kube-system <br />
- kubectl run --restart=Never --image=busybox static-busybox --dry-run=client -o yaml --command -- sleep 1000 > /etc/kubernetes/manifests/static-busybox.yaml  (Create a pod definition file in the manifests folder.) <br />
