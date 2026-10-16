# Docker Architecture and Components

## 1. Definition of Docker

Docker is an open-source platform used to build, package and run applications inside containers.

Containers include the application and its required dependencies, helping the application run consistently across compatible environments.

## 2. Docker Architecture

Docker follows a client-server architecture. The Docker client communicates with the Docker daemon to perform operations such as building images and running containers.

### Main Components of Docker Architecture

**1. Docker Client**

The Docker client is the interface through which users interact with Docker using commands.

Example: `docker run`

**Function:** Sends commands to the Docker daemon.

**2. Docker Daemon**

The Docker daemon is a background service that manages Docker objects such as images, containers, networks and volumes.

**Function:** Builds images and creates, runs and manages containers.

**3. Docker Host**

The Docker host is the computer or server where the Docker daemon manages containers and other Docker objects.

**Function:** Provides the environment and resources needed to run containers.

**4. Docker Registry**

A Docker registry stores and distributes Docker images.

Example: Docker Hub.

**Function:** Allows users to upload and download images.

**5. Docker Images**

A Docker image is a read-only template used to create containers. It contains the application and the files and dependencies needed to run it.

**Example:** A Python image used to run a Python application.

**6. Docker Containers**

A Docker container is a running instance of a Docker image. It provides an isolated environment for an application.

**Example:** A container running a college website.

## 3. How Docker Works

1. The user enters a Docker command through the Docker client.
    
2. The client communicates with the Docker daemon.
    
3. The daemon obtains the required image locally or downloads it from a registry.
    
4. The daemon creates a container from the image.
    
5. The application runs inside the container.
    

## 4. Important Docker Commands

|Command|Purpose|
|---|---|
|`docker --version`|Displays the Docker version.|
|`docker images`|Lists available images.|
|`docker ps`|Lists running containers.|
|`docker ps -a`|Lists all containers, including stopped ones.|
|`docker pull nginx`|Downloads the Nginx image.|
|`docker run nginx`|Creates and starts a container from the Nginx image.|
|`docker stop CONTAINER_ID`|Stops a running container.|

## 5. Advantages of Docker

1. Makes application deployment easier.
    
2. Provides consistent environments.
    
3. Uses fewer resources than running a separate full operating system for every application.
    
4. Supports application portability across compatible environments.
    
5. Makes scaling and managing applications easier.
    

## 6. Real-Time Example

Suppose a student develops a website using Python.

The student can package the application and its dependencies into a Docker image. Docker can then create a container to run the website.

The same image can be used on another compatible computer or server, reducing environment-related problems.

## 7. Summary

Docker is a containerization platform based on client-server architecture. Its main components include the Docker client, Docker daemon, Docker host, Docker registry, Docker images and Docker containers. These components work together to build, distribute and run applications.

[[09 - Docker Images, Containers and Repositories]]
