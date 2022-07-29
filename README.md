# spring-data-rest-mongodb
Rest api with spring data rest 
* [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/)

## Environment
* [Mongo oficial image](https://hub.docker.com/_/mongo)
Start environment
````
docker compose up -d
````
Connect mongodb command line with user root and password to database test
````
docker exec -it spring-data-rest-mongodb_mongo_1  mongosh -u root -p example -authenticationDatabase admin test
````
Connect mongo-express
````
http://localhost:8081/
````