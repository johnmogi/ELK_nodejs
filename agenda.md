1. minikube -ELK
/ aws cluster - 

https://theekshanawj.medium.com/kubernetes-deploying-a-nodejs-app-in-minikube-local-development-92df31e0b037

k apply -f app-deployment.yaml

create a new namespace and set it as default
k create namespace staging
kubectl config set-context --current --namespace=live
eval $(minikube docker-env)
2. 

deploy an app to k8s then kibana it train to connect to monmitor app