# In this project, accomplished the following.
   - Install Minikube, Kubectl.
   - create objects for following 4 services using config files to set up networking in k8s cluster.
```	
     - ClusterIP
     - NodePort
     - LoadBalancer
     - Ingress
```
- create deployment object with desired number of replicas (PODS ) and the container image to be used.
- used Ingress-Nginix controller to create an Ingress object for networking services.
- used following tags to create deployment objects apiversion, kind , metadata, service spec ( type, port, selector),POD spec(container name, image, ports).

- use database persistent volume claim.
- configure Docker CLI on local machine to use node docker service using eval $(minikube docker-env) command on current local terminal window.
- Understand the concept of kube-api server program of master in K8s cluster.
-Hands on with following commands
```
	- kubectl apply -f <YAML config file for creating objects>
	- kubectl get deployments
	- kubectl get pods
	- kubectl get pods -o wide ( To get IP address of PODS created )
	- kubectl describe < object type> <object name>
	- kubectl delete -f < YAML config file which created the object>
	- kubectl exec -ti <POD Name > sh ( To use the shell of the container )
	- kubectl logs <podsname> ( to get the logs of the container running on the POD )
	- kubectl get services.
	- minikube start / stop
	- kubectl cluster-info
	- minikube status
	- minikube ip

```

- creating deployments using both Imperative and declarative commands.
- familiar with minikube dashboard.
- understanding of Helm setup.
- understanding Kubernetes security with RBAC.Assigning tiller a service account created using RBAC.

