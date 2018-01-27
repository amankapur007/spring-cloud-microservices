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

3. Clone two more repo

https://github.com/amankapur007/eureka-server.git

and 

https://github.com/amankapur007/reservation-business-services.git

4. Also pull  the repo 

a. roomservices
b. config-server
c. rservationservices
d. eureka-server

and add in config folder

reservationbusinessservices.properties 
---------------------------------------------
server.port=8500

and commit it . (If you dnt commit locally it wont work)

5. Please checkout https://github.com/amankapur007/reservation-business-services.git

git pull 

git checkout Part-2-Feign

6. Please  Please checkout https://github.com/amankapur007/reservation-business-services.git

git pull

git checkout Part-2-Feign


