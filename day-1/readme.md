### Day 1: Kubernetes Basics & Architecture
 Topics: Kubernetes introduction, architecture, Master vs Worker nodes, Kubernetes components.
 Project: Set up Minikube/Kind, deploy Nginx.


 ## commands
 - kind create cluster --name local
 - docker ps
 - kind delete cluster -n local
 -  kind create cluster --config clusters.yml --name local
 - kubectl get nodes
 - kubectl get pods
 - kubectl get nodes --v=8
 - docker run -p 3005:80 nginx
 - kubectl run nginx --image=nginx --port=80
 - kubectl get pods
 - kubectl logs nginx
 - kubectl describe pod nginx
 - kubectl delete pod nginx
 - kubectl apply -f manifest.yml
 