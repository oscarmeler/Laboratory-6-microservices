# Web Engineering 2015-2016 / Microservices
Please, go to the [Wiki](https://github.com/UNIZAR-30246-WebEngineering/Laboratory-6-microservices/wiki) in order to get the instructions for this assignment.

## The two microservices are running and registered
![](https://github.com/oscarmeler/Laboratory-6-microservices/blob/master/screenshots/port_2222.png)

![](https://github.com/oscarmeler/Laboratory-6-microservices/blob/master/screenshots/port_3333.png)

## The service registration service has the two microservices registered
![](https://github.com/oscarmeler/Laboratory-6-microservices/blob/master/screenshots/registration.png)

![](https://github.com/oscarmeler/Laboratory-6-microservices/blob/master/screenshots/dashboard.png)

## A second account microservice is running in the port 4444 and it is registered
![](https://github.com/oscarmeler/Laboratory-6-microservices/blob/master/screenshots/port_4444.png)

## A brief report describing what happens when you kill the microservice with port 2222
After you kill the microservice in port 2222, the web service stop providing information about accounts because the micro service is down. If you try to do an operation, first shows a "Refused connection" message error. A few seconds later, you can see "No instances available for ACCOUNTS-SERVICE". 

After a little time the registration service detects that there is another service registered in port 4444. When the web service asks the registration service for another account service, it provides the service in port 4444. The web service will provide information about accounts again.
