# visit-counter-webapp
Simple Website visit counter app with NGINX proxy -> Flask -> {redis,postgres}, containerized with Docker.

# For Docker Compose Mode

$ git clone https://github.com/vishnuhd/visit-counter-webapp.git  
$ cd visit-counter-webapp  
$ docker-compose up  

# For Docker Swarm Mode

$ git clone https://github.com/vishnuhd/visit-counter-webapp.git  
$ cd visit-counter-webapp  
$ docker stack deploy --compose-file docker-stack.yml mywebapp  
