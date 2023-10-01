Spring Boot 3.1.4

A Simple Spring Boot Hellow World Web Application Deploying on Kubernetes

Steps
1. Go to https://github.com/srss-pocs/springboot-docker-helloworld
2. Push the image to docker hub using docker login and docker push
3. kubectl create secret docker-registry myregistrykey --docker-server=docker.io --docker-username=xxxxx --docker-password=xxxx --docker-email=xxxx@xxx.com
4. Create 2 files [pod and service yaml]
5. kubtl apply -f .
6. kubectl port-forward service/springboothelloworld-service 8082:8080 --address='0.0.0.0'

   
