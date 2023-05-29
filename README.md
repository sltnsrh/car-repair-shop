# Car Repair-Shop App

Reactive server application with microservice architecture.
Currently, it is in the progress of development.</br>
Aimed to conduct work of car repair shops: register customers, and their cars, manage information about them, 
make requests for service, count jobs and parts used for repairing, pay for the service, and so on. 
The app has possible roles: customer, manager, mechanic, and admin.
The entire activity of auto service encapsulates in one application.</br>
</br>
### Consist of elements and microservices: 
 - Eureka Server
 - Api-Gateway
 - Keycloak Auth Server
 - Account-Service
 - Car-Service
 - Order-Service
 - Mechanic-Service
 </br>
### Used databases:
 - Postgresql for Keycloak
 - MongoDb for Car-Service
