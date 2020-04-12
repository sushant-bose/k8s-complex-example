# k8s-complex-example

## Project diagram
![Project Diagram](https://raw.githubusercontent.com/sushant-bose/k8s-complex-example/master/ProjectDiagram.png)


## Project Deployment configs

### Total of 11 deployment configs (Declarative) 

* client-cluser-ip-service.yaml
* client-deployment.yaml
* database-persistent-volume-claim.yaml
* postgres-cluster-ip-service.yaml
* postgres-deployment.yaml
* redis-cluster-ip-service.yaml
* redis-deployment.yaml
* server-cluster-ip-service.yaml
* server-deployment.yaml
* worker-deployment.yaml


### And one Secret (Imperative)
```
kubectl create secret generic pgpassword --from-literal PGPASSWORD=asdf1234 
```
**--from-literal** accepts inputs inline inthe command, instead of a file

