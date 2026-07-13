# 🌐 Eureka Discovery Server

The central service registry for the Tech Store microservices architecture. This service utilizes Spring Cloud Netflix Eureka to enable dynamic service discovery, allowing the Order, Product, and Payment services to locate and communicate with each other without hardcoded IP addresses.

## 🛠️ Tech Stack
* Java 17
* Spring Boot 3.4+
* Spring Cloud Netflix Eureka Server

## ⚙️ Configuration
The server runs on the default Eureka port.
* **Port:** `8761`
* **Dashboard URL:** `http://localhost:8761`

## 🚀 Running the Application
Ensure this service is started **before** any other microservice to prevent connection timeouts.

```bash
./mvnw spring-boot:run
