This project demonstrates a simple microservice architecture implemented in Java with Spring. 
It consists of three microservices—Order Service, Inventory Service, and Shipment Service—that communicate through RabbitMQ as the message broker. The database used is PostgreSQL.

For security, Spring Security has been integrated into the Order Service. However, for more robust and scalable applications, 
you can implement a dedicated Security Microservice to manage authorization and permissions for all endpoints.

To use this microservice system, refer to password.txt, which contains the hashed version of the password 123456. 
Create a user with the username admin and assign it the ADMIN role in the roles table. This will grant the user full permissions across the system.
