- [Setup](#setup)
- [1. Running your first container](#1-running-your-first-container)
- [2. Webapps with Docker](#2-webapps-with-docker)
  - [2.1 Run a static website in a container](#21-run-a-static-website-in-a-container)
  - [2.2 Docker Images](#22-docker-images)
  - [2.3 Create your first image](#23-create-your-first-image)
    - [2.3.1 Create a Python Flask app that displays random cat pix](#231-create-a-python-flask-app-that-displays-random-cat-pix)
    - [2.3.2 Write a Dockerfile](#232-write-a-dockerfile)
    - [2.3.3 Build the image](#233-build-the-image)
    - [2.3.4 Run your image](#234-run-your-image)
    - [2.3.5 Push your image](#235-push-your-image)

## Setup

![setup1](images/setup1.png)

## 1. Running your first container

Pulling alpine image

![running_first_container1](images/running_first_container1.png)

Running container and commands in it

![running_first_container2](images/running_first_container2.png)

Running commands with interactive mode

![running_first_container3](images/running_first_container3.png)

Viewing run and existing containers

![containers](images/running_first_container4.png)

Viewing docker run command manual

![docker_run_help](images/running_first_container5.png)

## 2. Webapps with Docker

### 2.1 Run a static website in a container

Running container in detached mode

![3.1](images/3.1.png)

Stopping and removing container

![3.2](images/3.2.png)

Running site in container with random port and providing environment variables

![3.3](images/3.3.png)
![3.4](images/3.4.png)

Running site with specified port

![3.5](images/3.5.png)
![3.6](images/3.6.png)

Removing created containers

![3.7](images/3.7.png)

### 2.2 Docker Images

View images

![2.2.1](images/2.2.1.png)

Pulling ubuntu images with/without specifying image version

![2.2.2](images/2.2.2.png)

### 2.3 Create your first image

#### 2.3.1 Create a Python Flask app that displays random cat pix

[flask-app folder](flask-app/)

![2.3.1](images/2.3.1.png)

#### 2.3.2 Write a Dockerfile

![2.3.2](images/2.3.2.png)

#### 2.3.3 Build the image

![2.3.3](images/2.3.3.png)

#### 2.3.4 Run your image

![2.3.4.1](images/2.3.4.1.png)
![2.3.4.2](images/2.3.4.2.png)

#### 2.3.5 Push your image

![2.3.5.1](images/2.3.5.1.png)
