# Deploy Docker Containers with Docker Cloud

Docker Cloud is a service that automates the deployment of Docker images.
Docker Cloud to easily deploy Docker containers based on Dockerfiles in a GitHub repository.

# Getting started
 It is exactly the same as the code in `02-docker-compose` but with the addition of a Dockerfile in the `website` directory.

To run the application, 
 `cd` into this directory 
 Install all the libraries mentioned in requirements.txt file 
 and run `docker-compose up`.
 The product service and the website will start (if necessary, docker-compose will automatically build the containers).