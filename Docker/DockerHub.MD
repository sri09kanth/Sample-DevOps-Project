## What is Docker Hub Registry

Docker Hub is a cloud-based registry service which allows you to link to code repositories, build your images and test them, stores manually pushed images, and links to Docker Cloud so you can deploy images to your hosts. It provides a centralized resource for container image discovery, distribution and change management, user and team collaboration, and workflow automation throughout the development pipeline.
##### Ref URL : https://docs.docker.com/docker-hub/

1. Create a docker hub account in https://hub.docker.com/

1. Pull a docker imae 
   
   docker pul
  
. pull a docker  with the old vers
   ```
   docker pull ubuntu:16.04
   ```

1. create a custom tag to the docker image
   ```sh
   docker tag ubuntu:latest valaxy/ubuntu:demo
   ```
1. login to your docker hub registry 
   ```sh
   docker login
   docker push valaxy/ubuntu:demo
   ```

### testing 
1. Remove all images in docker server 
   ```
   docker image rm -f <Image_
   ```

1. Pull your custom image from your docker account
   ```sh
   docker pull valaxy/ubuntu:demo
   ```

