# DockerHelloWorld


This is sample project for Hello World which contains docker file to test on docker container.
It uses java 11.

docker pull openjdk - This will pull openjdk image 

docker images : list all your docker images


docker ps -a  :  lists all the Docker containers 

docker ps : list only the running containers.

docker build -t my-app-image .  :-build docker image with my-app-image


docker image prune -a --force  :-delete all the images from container

docker run --rm my-app-image


docker run -it -p 8000:8000 my-app-image

![image](https://github.com/chaitalishah/DockerHelloWorld/assets/13629726/22b82e57-2d32-4175-9e9e-3a03a6963357)
