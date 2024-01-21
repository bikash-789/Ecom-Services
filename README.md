# Microservices with Spring Boot and KeyCloak Authentication

Welcome to the Microservices with Spring Boot and KeyCloak Authentication project! This repository contains a set of microservices built using the Spring Boot framework, showcasing a modular and scalable architecture.

## Project Overview

The project consists of the following microservices:

- **Product-Service:** Manages product-related functionalities.
- **Inventory-Service:** Handles inventory-related operations.
- **Order-Service:** Facilitates order processing and management.
- **Discovery-Service:** Enables service discovery within the microservices architecture.
- **API-Gateway:** Acts as the entry point for external requests, routing them to the appropriate microservice.

## Project Structure

The project is organized with each microservice in its respective directory:

microservices-spring-boot/
|-- product-service/
|-- inventory-service/
|-- order-service/
|-- discovery-service/
|-- api-gateway/
|-- notification-service/


## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/microservices-spring-boot.git
   
2. Navigate to a microservice (e.g., product-service):
   cd microservices-spring-boot/product-service

3. Build the microservice using Maven:
   mvn clean install
   Repeat these steps for each microservice.

4. Authentication with KeyCloak
KeyCloak has been integrated into the project to provide authentication to API routes.
Ensure that KeyCloak is properly configured and running. Update KeyCloak configurations in each microservice's application.properties file if necessary.

5. Usage
   Start the microservices in the following order:
   -Discovery Service
   -Other microservices
   -API Gateway

6. Access the services through the API Gateway:
   http://localhost:8080/api/product
   http://localhost:8080/api/inventory
   http://localhost:8080/api/order

## Dependencies
Each microservice uses different Maven dependencies tailored to its functionality. Refer to the respective pom.xml files for details.

Happy Coding! 🚀


