# ERS Application

**Enterprise Resource & Project Management System**

## Tech Stack
- Java 17
- Spring Boot 3.4.5
- PostgreSQL
- Maven
- Redis
- RabbitMQ

## Getting Started

1. Ensure PostgreSQL is running on port 5432.
2. Create a database: `CREATE DATABASE ers_app;`
3. Configure `src/main/resources/application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/ers_app
   spring.datasource.username=user_ers
   spring.datasource.password=pass_ers
