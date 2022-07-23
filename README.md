# k8s-start
k8s-start

-----




# start
````
microk8s.kubectl apply -f s-deployment.yaml
microk8s.kubectl apply -f s-service.yaml

microk8s.kubectl apply -f b-deployment.yaml
microk8s.kubectl apply -f b-service.yaml
````

# delete
````

microk8s.kubectl delete -f s-deployment.yaml
microk8s.kubectl delete -f s-service.yaml

microk8s.kubectl delete -f b-deployment.yaml
microk8s.kubectl delete -f b-service.yaml

````

# brower

````
curl http://us01.tool1314.com:30333/

curl http://us01.tool1314.com:30322/
````