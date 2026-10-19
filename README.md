# Employee-Address Microservices

## Overview
Employee-Address is a backend application built using Spring Boot and a microservices architecture. It consists of two core microservices: Employee Service and Address Service. The services are connected through an API Gateway, with Eureka Server providing service discovery.

## Tech Stack
- **Language:** Java
- **Framework:** Spring Boot
- **Architecture:** Microservices
- **Service Discovery:** Netflix Eureka
- **Routing:** Spring Cloud API Gateway
- **API Testing:** Postman

## Key Features
- Separate Employee and Address microservices.
- Service registration and discovery using Eureka.
- Centralized request routing through API Gateway.
- REST API-based communication.
- Independent service organization for improved maintainability.

## Architecture

Client → API Gateway → Employee Service / Address Service

Eureka Server enables service registration and discovery.

## Getting Started
1. Clone the repository.
2. Configure the application properties for each service.
3. Start the Eureka Server.
4. Start the Employee and Address services.
5. Start the API Gateway.
6. Test the available endpoints using Postman.

## Learning Outcomes
- Understanding microservices architecture.
- Implementing service discovery with Eureka.
- Routing requests through an API Gateway.
- Configuring and running multiple Spring Boot services.

## Future Improvements
- Add centralized configuration management.
- Implement centralized logging and monitoring.
- Add automated integration tests.
- Containerize services using Docker.

## Author
Lovedeep Mahlan

**Technologies:** Java | Spring Boot | Microservices | Eureka | API Gateway | REST APIs
