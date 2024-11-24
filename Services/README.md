# Types

**NodePort** where the service makes an internal port accessible on a port on the node. <br />
The second is **CluserIP**, and in this case, the service creates a **virtual IP inside** the luster to enable communication between different services, such as a set of frontend servers to a set of backend servers. <br />
The third type is a LoadBalancer, where it provisions a load balancer for our application in supported cloud providers. <br />


# Commands

- kubectl get serviceaccount -n kube-system <br />
- kubectl get clusterrolebinding  <br />
- kubectl replace --force -f /tmp/kubectl-edit-XXXXX.yaml

