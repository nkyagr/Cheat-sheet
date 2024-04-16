# Cheat-sheet
docker pull <image name> - used to pull images from the docker repository.

docker ps - used to list the running containers

docker exec -it <container id> bash - used to access the running container

docker stop <container id> - used to stop a running container

docker commit <conatainer id> <username/imagename> - used to creates a new image of an edited container on the local system

docker push <username/image name> - used to push an image to the docker hub repository

docker rmi <image-id> - used to delete an image from local storage

docker build <path to docker file> - used to build an image from a specified docker file

docker history <image_name> - used to examine the evolution of a Docker image or its constituent parts

docker logout [REGISTRY_URL] - used to log out of a Docker registry or to delete the credentials used to login with it 
