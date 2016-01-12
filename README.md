# Web Engineering 2015-2016 / Microservices
Please, go to the [Wiki](https://github.com/UNIZAR-30246-WebEngineering/Laboratory-6-microservices/wiki) in order to get the instructions for this assignment.

## The two microservices are running and registered
![](https://github.com/oscarmeler/Laboratory-6-microservices/blob/master/screenshots/port_2222.jpg?raw=true)
![](https://raw.github.com/oscarmeler/Laboratory-6-microservices/master/screenshots/port_3333.jpg?raw=true)

## The service registration service has the two microservices registered
![](https://github.com/oscarmeler/Laboratory-6-microservices/blob/master/screenshots/dashboard.jpg?raw=true)

## A second account microservice is running in the port 4444 and it is registered
![](https://github.com/oscarmeler/Laboratory-6-microservices/blob/master/screenshots/registration.jpg?raw=true)
![](https://github.com/oscarmeler/Laboratory-6-microservices/blob/master/screenshots/port_4444.jpg?raw=true)

## A brief report describing what happens when you kill the microservice with port 2222
After you kill the microservice with port 2222, if you try to do an operation, first shows a "Refused connection" message error. A few seconds later, you can see "No instances available for ACCOUNTS-SERVICE". 

After a little time the web service shows the other account service running in the 4444.
