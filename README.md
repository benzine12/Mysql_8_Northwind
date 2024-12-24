Link to Docker Hub:

https://hub.docker.com/r/archi95/sql8_northwind

username: root
password: root_password

to isntall the docker run :

docker pull archi95/sql8_northwind:latest

docker run -d --name sql8_northwind -e MYSQL_ROOT_PASSWORD=root_password -p 3306:3306 archi95/sql8_northwind:latest

