Create Docker container:

docker-compose up

To see list of containers
docker ps

To view images
docker images

Access the running container
docker exec -it mysql-snippets_db_1 bash

Coonnect to MySQL Server
mysql-uroot -proot

SHOW DATABASES;

USE Product_db;

SHOW tables;

select * from product;

https://github.com/lifeparticle/MySQL-Snippets
