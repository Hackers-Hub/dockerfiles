# dockerfiles
Docker build files

## Instructions
Inside each of folder there is a build file and a docker compose yml file.
You can either download both and just do a docker-compose up -d and it will automatically build the customized image and deploy the container.

Alternatively: You can build the file yourself and run it with docker container run command simply as.
```
docker build -t nginx-hackershub .
docker container run -d -p 80:80 nginx-hackershub
```
And you can now access the webapp via http://localhost:80
