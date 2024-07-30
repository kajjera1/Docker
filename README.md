# Docker

Docker is a containerization platform that provides easy way to containerize your applications, which means using Docker you can build container images, run the images to create containers and also push these containers to container regestries such as DockerHub

## ARCHITECTURE:
DOCKER CLIENT, 
DOCKER DAEMON, 
DOCKER HOST, 
DOCKER REGISTRY

## Docker components

Docker Client.-> 
Performs Docker build pull and run operations to open up communication with the Docker Host. The Docker command then employs Docker API to call any queries to run.

Docker Host.->
 Contains Docker daemon, containers, and associated images. The Docker daemon establishes a connection with the Registry. The stored images are the type of metadata dedicated to containerized applications.

Registry.-> 
 This is where Docker images are stored. There are two of registry, a public registry and a private one. Docker Hub and Docker Cloud are two public registries available for use by anyone.

## Docker registries

A Docker registry stores Docker images. Docker Hub is a public registry that anyone can use, and Docker is configured to look for images on Docker Hub by default. You can even run your own private registry.

## Docker file

Dockerfile is a file where you provide the steps to build your Docker Image.

 ##instruction present in docker file [components in docker file]
 
 1.FROM:  Specifies the base image to use for the build.
 
 2.RUN:  Executes commands in the shell of the container during the build process.
 
 3.COPY:  Copies files or directories from the host machine into the image's filesystem.
 
 4.CMD:  Specifies the default command to run when the container starts. 
 
 5.EXPOSE:  Informs Docker that the container listens on specific network ports at runtime.  It does not actually publish the ports.
 
 6.ENV:  Sets environment variables inside the container.
 
 7.ENTRYPOINT:  Configures the container to run as an executable. 
 
 8.LABEL:  Adds metadata to the image.
 
## CONTAINERS

Containers will not have os by default.

cant able to install pacakages

cant able to deploy the app.
