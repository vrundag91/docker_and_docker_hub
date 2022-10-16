<h1>Assignment 2 Docker & Docker Hub</h1>

<h2>Task 1</h2>

<h5>Demonstration of Basic Docker Command</h5>

<p>1. Docker --version : This command use to check the version of the docker and if it is up and running</p>

`docker --version`

![Docker Version](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-version.PNG)

<hr>

<p>2. Docker Pull : Pull an image or a repository from a registry</p>

`docker pull <docker image name>`

![Docker pull](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-pull.PNG)

<hr>

<p>3. Docker run : This command is used to run the image/container locally</p>

`docker run -d -p <host port number> : <container port number> <docker image name>`

<p><b>Example:</b></p>

`docker run -d -p 80:80 docker/getting-started`

![Docker run](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-run.PNG)

<hr>

<p>4. Docker ps : This command is used to list all the containers</p>

`docker ps`

`docker ps -a`

![Docker ps](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-ps.PNG)

<hr>

<p>5. Docker images : This command list all the images available in docker</p>

`docker images`


![Docker images](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-images.PNG)

<hr>

<p>6. Docker exec :This command is used to access the running container</p>

`docker exec -it <container id> bash`


![Docker images](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-exec.PNG)

<hr>

<p>7. Docker stop :This command stops a running container</p>

`docker stop <container id>`


![Docker images](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-stop.PNG)

<hr>

<p>8. Docker Kill :This command kills the container by stopping its execution immediately. The difference between ‘docker kill’ and ‘docker stop’ is that ‘docker stop’ gives the container time to shutdown gracefully, in situations when it is taking too much time for getting the container to stop, one can opt to kill it</p>

`docker kill <container id>`


![Docker images](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-kill.PNG)

<hr>

<p>9. Docker commit :This command creates a new image of an edited container on the local system</p>

`docker commit <conatainer id> <username/imagename>`


![Docker images](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-commit.PNG)

<p>Check the Docker image in Docker Desktop:</p>

![Docker images](https://github.com/vrundag91/docker_and_docker_hub/blob/main/docker-screenshots/docker-commit-1.PNG)

<hr>







