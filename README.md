# Helm
### 1- Pushing python and redis images to dockerhub. 

Docker.io/salashraf/redis

Docker.io/salashraf/python


Repo link: https://hub.docker.com/repositories/salashraf

### 2- Create python and redis charts.

helm create redis-chart

helm create python-chart

### 3- Edit values.yaml files in both folders. 

### 4- Adding configmap part in python deployment.

### 5- 
helm install redis ./redis-chart/

helm install python-app ./python-chart/
