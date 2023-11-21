# Microservices
 
- Setup steps with Mysql and MongoDB running steps
- Branch info

docker run --name mongodb -d -p 27017:27017 mongodb/mongodb-community-server

docker run --name local-Vik-mysql -v myDbData:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=password -d -p 3306:3306 mysql:latest
