# Commands

kubectl create -f replicaset-definition.yaml   (must use -f)  <br />
kubectl get replicaset (to see the list of replicaset creted)  <br />
kubectl delete pod PODNAME  <br />
kubectl replace -f  replicaset-definition.yaml  - to replace  <br /> 
kubectl scale -replicas=6 -f replicaset-definition.yaml (modifying the number of the replicas but this will not change the number in the file already defined)  <br />
kubectl scale - -replicas= 5 replicaset <replicaset name>   ## Scale up  <br />
kubectl scale - -replicas= 1 replicaset <replicaset name>   ## Scale down  <br />
