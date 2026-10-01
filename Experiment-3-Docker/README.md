# Experiment 3 – Docker Installation and Basic Commands

## Aim

To install Docker and execute basic Docker commands.

## Docker Installation

Docker Desktop was installed on Windows using the WSL 2 backend.

## Commands Executed

### 1. Check Docker Version

```cmd
docker --version
### 2. Check Docker Information

docker info

### 3. Pull Hello World Image

docker pull hello-world

### 4. List Docker Images

docker images

### 5. Run Hello World Container

docker run hello-world

### 6. Pull Ubuntu Image

docker pull ubuntu

### 7. Run Ubuntu Container

docker run -it ubuntu

### 8. List Running Containers

docker ps

### 9. List All Containers

docker ps -a

### 10. Stop Container

docker stop <CONTAINER_ID>

### 11. Remove Container

docker rm <CONTAINER_ID>

### 12. Remove Docker Image

docker rmi ubuntu

## Result

Docker was successfully installed and verified. Docker images were pulled, containers were created and executed, and basic Docker management commands were performed successfully.