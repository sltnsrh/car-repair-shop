# Car Repair-Shop App

Reactive server application with microservice architecture.
Currently, it is in the progress of development.</br>
Aimed to conduct work of car repair shops: register customers, and their cars, manage information about them, 
make requests for service, count jobs and parts used for repairing, pay for the service, and so on. 
The app has possible roles: customer, manager, mechanic, and admin.
The entire activity of auto service encapsulates in one application.</br>
</br>
### Consist of elements and microservices: 
 - [Eureka Server](https://github.com/sltnsrh/car-repair-eureka-server)
 - [Api-Gateway](https://github.com/sltnsrh/car-repair-api-gateway)
 - Keycloak Auth Server
 - [Account-Service](https://github.com/sltnsrh/car-repair-account-service)
 - [Car-Service](https://github.com/sltnsrh/car-repair-car-service)
 - [Order-Service](https://github.com/sltnsrh/car-repair-order-service)
 - [Mechanic-Service](https://github.com/sltnsrh/car-repair-mechanic-service)
 </br>
### Used databases: 
 - Postgresql for Keycloak
 - MongoDb for Car-Service
 - MongoDb for Order-Service
</br>
Approximate scheme of services architecture. Relations can be differ.
`car-repair-shop-scheme.pdf`