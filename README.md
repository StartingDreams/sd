# Starting Dreams CMS Core
Starting Dreams CMS is a learning project.

Because of this I'm using many different technologies. This is more about using docker containers and clusters than creating a MVP.

## Docker Containers

#### api
Apache / PHP
Lumen Framework

Dependencies
* mysql
* redis 

#### frontend
Node / Angular

Dependencies
* mongo 
* redis

#### nginx
NGINX Reverse proxy server.

Routing:
/api/* to api container
/* to frontend container

#### mysql
MariaDB server

#### mongo
MongoDB

#### redis
Redis server



