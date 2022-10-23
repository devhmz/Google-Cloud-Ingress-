# Google-Cloud-Ingress-

docker pull image 
docker run image:tag
docker exec -it container sh 


create docker image with the new container : 
docker commit [ContainerID] [NewImageName]  

How to pull image to docker hub  
  login : docker login -u username 

How to tag image
  docker tag image:tag  username/image

How to push image 
  docker push username/image
   
  
  
# Apply 
  kubectl apply -f web-developement.yaml 
  kubectl apply -f web-service.yaml 
  kubectl apply -f basic-ingress.yaml 
  
# Show external IP Address:
  kubectl get ingress 
