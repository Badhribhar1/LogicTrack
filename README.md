# LogiTrack

**LogiTrack** is a high-performance inventory and logistics management backend built with **Java 25** and **Spring Boot**. It enables real-time tracking of product SKUs across multiple warehouse locations and provides automated dispatch logic for order fulfillment.

## Tech Stack
* **Language:** Java 25
* **Framework:** Spring Boot 3.4
* **Database:** PostgreSQL
* **ORM:** Spring Data JPA / Hibernate
* **Build Tool:** Maven
* **Tools:** Lombok, VS Code

## Key Features
* **Inventory Synchronization:** Manage stock levels across diverse regional hubs.
* **Intelligent Fulfillment:** Backend logic to determine the optimal warehouse for order dispatching.
* **RESTful Architecture:** Clean API endpoints for product and warehouse management.
* **Database Persistence:** Production-ready PostgreSQL integration.

## Getting Started
* **Database:** Create a Postgres DB named `logistics_db`.
* **Config:** Set your credentials in `src/main/resources/application.properties`.
* **Run:** ```bash
  ./mvnw spring-boot:run
