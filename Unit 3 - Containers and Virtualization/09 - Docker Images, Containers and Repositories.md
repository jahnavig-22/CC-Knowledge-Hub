# Docker Images, Containers and Repositories

## 1. Docker Image

### Definition

A Docker image is a read-only template used to create Docker containers. It contains the application code, libraries, dependencies and instructions needed to run an application.

### Features

- Read-only template.
    
- Can be reused to create multiple containers.
    
- Can be stored and shared through a Docker registry.
    
- Helps maintain a consistent application environment.
    

### Example

A Python image provides the environment required to run Python applications.

## 2. Docker Container

### Definition

A Docker container is an isolated, runnable instance of a Docker image.

### Features

- Runs an application in an isolated environment.
    
- Can be started, stopped and removed.
    
- Shares the host operating system kernel.
    
- Can be created from an existing image.
    

### Example

A container created from a Python image can run a Python program.

## 3. Docker Repository

### Definition

A Docker repository is a collection of related Docker images, often with different versions identified by tags.

### Example

The `nginx` repository contains images for the Nginx web server.

### Features

- Stores related images.
    
- Supports image versioning through tags.
    
- Helps developers share and distribute images.
    

## 4. Docker Registry

### Definition

A Docker registry is a service that stores and distributes Docker images.

**Example:** Docker Hub is a popular public Docker registry.

A registry can contain multiple repositories, and each repository can contain multiple image versions.

## 5. Difference Between Image, Container, Repository and Registry

|Term|Meaning|
|---|---|
|Docker Image|Template used to create containers.|
|Docker Container|Running or stopped instance created from an image.|
|Docker Repository|Collection of related images and their versions.|
|Docker Registry|Service that stores and distributes repositories of images.|

## 6. Important Docker Commands

|Command|Purpose|
|---|---|
|`docker pull nginx`|Downloads the Nginx image.|
|`docker images`|Lists locally available images.|
|`docker run nginx`|Creates and starts a container from the Nginx image.|
|`docker ps`|Lists running containers.|
|`docker stop CONTAINER_ID`|Stops a container.|
|`docker push USERNAME/IMAGE_NAME`|Uploads an image to a registry, provided authentication and permissions are configured.|

## 7. Real-Time Example

Suppose a student develops a web application.

1. The student creates a Docker image containing the application and its dependencies.
    
2. Docker creates a container from that image to run the application.
    
3. The student stores the image in a repository.
    
4. The repository is hosted in a registry such as Docker Hub.
    
5. Another developer downloads the image and runs it in a compatible environment.
    

## 8. Summary

A Docker image is a template, a container is an instance created from that template, a repository groups related images, and a registry stores and distributes repositories. These components help developers package, share and run applications efficiently.

[[Home - Cloud Computing]]
