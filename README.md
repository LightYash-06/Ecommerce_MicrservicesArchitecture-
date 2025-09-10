🛒 Ecommerce_MicroservicesArchitecture

E-Commerce Microservices project built with Spring Boot, Spring Cloud, Docker, and Kubernetes.
Includes service discovery, API gateway, messaging with Kafka/RabbitMQ, security with Keycloak, and observability with Zipkin & Micrometer.

📖 Spring Boot Microservices eCommerce Project

This repository contains a demo eCommerce platform built with Java Spring Boot using a microservices architecture.
It is inspired by the Spring Boot Microservices with Spring Cloud, Docker & Kubernetes course.

🚀 Features

Microservices: Product, Order, User/Auth, Payment

API Gateway with Spring Cloud Gateway

Service Discovery using Eureka

Messaging & Events with Kafka and RabbitMQ

Security: OAuth2 & JWT with Keycloak

Databases: PostgreSQL & MongoDB

Resilience & Fault Tolerance with Resilience4J

Observability: Zipkin, Micrometer

Containerization & Orchestration: Docker + Kubernetes

🏗️ Architecture
Client → API Gateway → Microservices (Product, Order, Payment, User)  
       ↳ Service Discovery (Eureka)  
       ↳ Messaging (Kafka/RabbitMQ)  
       ↳ Security (Keycloak, JWT)  
       ↳ Observability (Zipkin, Micrometer)  

🛠️ Tech Stack

Backend: Spring Boot, Spring Cloud

Messaging: Kafka, RabbitMQ

Security: Keycloak, OAuth2, JWT

Databases: PostgreSQL, MongoDB

Infrastructure: Docker, Kubernetes (K8s), Eureka

Monitoring: Zipkin, Micrometer
