# Docker lesson 1
## In this lesson you will deploy nginx container on your local machine
### You will learn next docker commands:
### 1. `docker pull`
### 2. `docker run`
### Pre-requisities:
1. Docker should be installed (installation guides [Linux](https://docs.docker.com/engine/install/ubuntu/), [MacOS and Windows](https://www.docker.com/products/docker-desktop))
2. If you are using Linux, you should configure an ability to run docker commands as a non-root user, otherwise you should add `sudo` before each command
### Tasks
1. Get docker nginx image from DockerHub. Use `docker pull` command.
2. Run the container on your local machine by using `docker run` command. 
>Don't forget to add ***port binding*** to your image to make it accessible from your local machine
3. Create an `docker_run.sh` script and place a command into this script