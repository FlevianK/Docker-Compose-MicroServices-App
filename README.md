# Docker-Compose-MicroServices-App
Building Docker-Compose based MicroServices for a Flask Application¶

**Precondition**
* Install docker(1.6.0 or above)
* docker-compose(1.3.1 or above)
* clone this repo

**Run docker script**
1. To get the containers up, build the images and start services
```sh
docker-compose build
```

2. To start all containers
```sh 
docker-compose up -d
```

3. to create database in the container
```sh
docker-compose run web /usr/local/bin/python create_db.py
```

4. To view environment variables
```sh
docker-compose run web env
```

5. To view logs
```sh
docker-compose logs
```

6. To stop all services
```sh
docker-compose stop.
```
