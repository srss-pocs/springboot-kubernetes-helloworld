A Simple Spring Boot Hellow World Web Application Deploying on Kubernetes

Steps
1. Go to https://github.com/srss-pocs/springboot-docker-helloworld
2. Push the image to docker hub using docker login and docker push
3. Create 2 files [pod and service yaml]
4. kubtl apply -f .
5. kubectl port-forward service/springboothelloworld-service 8082:8080 --address='0.0.0.0'

   
