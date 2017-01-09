## Cuddle Eureka Server

#### Environment variable

1. EUREKA_SERVER_PORT
1. EUREKA_SERVER_NAME

Map relevant ports

docker run -it -d --name=instruction-eureka-server -p 7681:7681 -e EUREKA_SERVER_PORT=7681 -e EUREKA_SERVER_NAME=instruction-eureka-server cuddle/eureka-server:latest

