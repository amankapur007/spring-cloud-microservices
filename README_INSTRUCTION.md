For full project clone the below gits

1. https://github.com/amankapur007/spring-cloud-microservices-config.git
2. https://github.com/amankapur007/spring-cloud-microservices-config-server.git
3. https://github.com/amankapur007/eureka-server.git
4. https://github.com/amankapur007/spring-cloud-microservices.git 
5. https://github.com/amankapur007/reservation-business-services.git

All these are linked together

In 

spring-cloud-microservices-config-server/src/main/resources/application.properties

--------------------------------------------------------------
server.port=9000
spring.cloud.config.server.git.uri={/home/aman/Downloads/config} --> Replace with the uri where you have config folder cloned in Step 1


