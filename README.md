# Docker Compose Spring Boot and MySQL example

## Run the System
We can easily run the whole with only a single command:
```bash
mvn clean package -pl api-gateway,service1,service2,service-discovery -am
```
```bash
docker-compose up
```
Docker will pull the MySQL and Spring Boot images (if our machine does not have it before).

The services can be run on the background with command:
```bash
docker-compose up -d
```

## Stop the System
Stopping all the running containers is also simple with a single command:
```bash
docker-compose down
```

If you need to stop and remove all containers, use the command:
```bash
docker-compose down --rmi all
```
