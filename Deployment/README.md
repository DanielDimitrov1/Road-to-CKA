# Commands

- kubectl rollout status deployment/nginx-deployment <br />
- kubectl create deployment --image=nginx nginx  <br />
- kubectl create deployment --image=nginx nginx --dry-run=client -o yaml <br />
- kubectl create deployment --image=nginx nginx --dry-run=client -o yaml > nginx-deployment.yaml  ( Generates Deployment YAML file (-o yaml). Don’t create it(–dry-run) and save it to a file) <br /> 

- kubectl create deployment --image=nginx nginx --replicas=4 --dry-run=client -o yaml > nginx-deployment.yaml (specify the --replicas option to create a deployment with 4 replicas) <br /> 

- kubectl create deployment --help
