This Part requires few configuration

1. clone the git repository from 

https://github.com/amankapur007/spring-cloud-microservices-config.git

config folder will be there , inside that we have roomservices.properties

2. clone the git repository

https://github.com/amankapur007/spring-cloud-microservices-config-server.git

open application.properties of the above cloned project

server.port=9000
spring.cloud.config.server.git.uri=/home/aman/Downloads/config {path where you have config cloned from Step 1}

Run the server 

