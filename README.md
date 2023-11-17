# docker_flask_homework
This is assignment #8 for HHA504


## Part 1:  1. Setting Up and Dockerizing a Flask App:
### Build the Docker image and run the container.
#### Document the build and run commands you used.
The docker build command I used was `docker build -t docker_example_1`
The docker run command I used was `docker run -d -p 5001:5000 docker_example_1`

## Part 1:  2. Documentation:
### Document the steps you took to Dockerize the Flask application.
I created a docker file that uses port 5000 to run the application, from there I used the docker build and docker run commands to docerize the application. 


## Part 2:  2. Dockerizing with Docker Compose:
### Use Docker Compose to build and run your multi-container setup.
#### Document the specific commands used to manage the Docker Compose lifecycle.
`docker-compose up`

## Part 2:  3. Documentation:
### Document the process of setting up and running the two Flask applications with Docker Compose.
I created docker files for both applications, from there I changed the ports to be used from 5000 and 5001 to 8080 and 8081. 
I then created a docker compose file to build and run the applications. 

### Discuss the role of Docker Compose and how it differs from using Docker alone.
Docker compose builds and runs the application and also allows for multiple containers to be run using a single source. 
With docker files alone you can only build and run one container at a time. 

### Note any challenges encountered and how they were addressed.
I had some challenges with using the 5000 port for part 2, but after switching to 8080 and 8081 my application worked as expected. 
