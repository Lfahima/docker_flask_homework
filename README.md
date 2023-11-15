# docker_flask_homework
This is assignment #8 for HHA504


## Part 1:
#### Build the Docker image and run the container.
### Document the build and run commands you used.
I used the docker build and docker run to build and run the flask apllication. 
# Docker build command: docker build -t docker_example_1 .     
# Docker run command: docker run -d -p 5001:5000 docker_example_1



The process of Dockerizing the applications in both parts.
I created a docker file that uses port 5000 to run the application from there I used docker build and docker run commands to docerize the application. 

## Part 2:
#### Document the specific commands used to manage the Docker Compose lifecycle.
docker-compose up 

#### Documentation:
Document the process of setting up and running the two Flask applications with Docker Compose.
created docler files for both application from there chnaged the ports to be used from 5000, 5001 to 8080, 8081 
then created a docker compose file to build and run the application. 

Discuss the role of Docker Compose and how it differs from using Docker alone.
Docker compose builds and runs the application and also allows for multiple containers to be run using a single source. With docker files alone you can only build and run one container at a time. 

Note any challenges encountered and how they were addressed.
I had some challenges with using the 5000 port for part 2 but after switching to 8080 and 8081 my application worked as expected. 