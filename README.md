# kubernetes
# setting up hadoop cluster on kubernetes. 

first creating the service

kubectl create -f cdh-service.yaml 

creating the rc controller

kubectl create -f cdh-rc.yaml

# setting up solr containers.

first creating the service for solr pods.

kubectl create -f solr-service.yaml

creating the rc controller. 

kubectl create -f solr-rc.yaml
