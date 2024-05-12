# Docker 2.0
Desafio 01 (postgres):
```
docker container run -d -p 5432:5432 -e POSTGRES_DB="curso_docker" -e POSTGRES_USER="docker_usr" -e POSTGRES_PASSWORD="docker_pwd" postgres
```

Desafio 01 (mySql):
```
docker container run -d -p 3306:3306 -e MYSQL_DATABASE="docker_db" -e MYSQL_USER="docker_usr" -e MYSQL_PASSWORD="docker_pwd" mysql
```