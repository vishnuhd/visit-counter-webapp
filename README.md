# visit-counter-webapp
Simple website visit counter app with NGINX proxy -> Flask -> {redis,postgres}, containerized with Docker.

For demo, clone the repo and select one of below Modes   

```
$ git clone https://github.com/vishnuhd/visit-counter-webapp.git   
$ cd visit-counter-webapp   
```

# For Docker Compose Mode
```
$ docker-compose up   
```

# For Docker Swarm Mode
```  
$ docker stack deploy --compose-file docker-stack.yml mywebapp   
```

# For Kubernetes Deployment Mode
``` 
$ kubectl create -f k8-deployment   
```
OR
``` 
$ kubectl create -f k8-specifications/   
```
