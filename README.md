# ELK_nodejs
try this:
https://learnk8s.io/deploying-nodejs-kubernetes

 k port-forward svc/prometheus-main 9090:9090 -n m
onitoring
 k port-forward svc/grafana 3000:3000 -n monitoring
http://0.0.0.0:9090/graph

the work plan is:

deploy a basic nodejs app to k8s - done.

- prometheus grafana? maybe next in line.
- use helm chart to install ELK


https://logz.io/blog/deploying-the-elk-stack-on-kubernetes-with-helm/

kubectl port-forward svc/elasticsearch-master 9200


connect json / docker logs into kibana


