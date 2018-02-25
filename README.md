# simple-docker-template
Creating a simple docker template for a Nginx, PHP & MySQL application

### Docker Setup
- [Docker for Mac](https://docs.docker.com/docker-for-mac/)
- [Docker for Linux](https://docs.docker.com/engine/installation/linux/)
- [Docker for Windows](https://docs.docker.com/docker-for-windows/)

### Docker Basic

Run the command bellow at the root of the project to bring the containers up```ssh
$ docker-compose up -d
```

or 

pipe the docker-compose logs to a docker-compose.logs file to understand if anything went wrong
```ssh
$ docker-compose up -d > docker-compose.logs
```

Access the app on http://localhost:8080/ (substitute localhost for the IP address of the nginx container)

Run the command below at the root of the project to bring bring the containers down 
```ssh
$ docker-compose down
```

### Contribute
Submit a Pull Request!