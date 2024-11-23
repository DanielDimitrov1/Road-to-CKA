# Commands

- kubectl rollout status deployment/nginx-deployment <br />
- kubectl create deployment --image=nginx nginx  <br />
- kubectl create deployment --image=nginx nginx --dry-run=client -o yaml <br />
- kubectl create deployment --image=nginx nginx --dry-run=client -o yaml > nginx-deployment.yaml  ( Generates Deployment YAML file (-o yaml). Don’t create it(–dry-run) and save it to a file) <br />


- kubectl create deployment --image=nginx nginx --replicas=4 --dry-run=client -o yaml > nginx-deployment.yaml (specify the --replicas option to create a deployment with 4 replicas) <br /> 


## Rollout deployment

- kubectl **set** image deployment/myapp-deployment nginx=nginx:1.9.1 <br />
- kubectl **create** deployment --help <br />
- kubectl rollout **status** deployment/myapp-deployment <br /> 
- kubectl rollout **history** deployment/myapp-deployment <br />
- kubectl rollout **undo** deployment/myapp-deployment <br />

