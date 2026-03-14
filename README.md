# School Management App (Java & Spring Boot)

A modern school data management system developed as part of the Coding Factory program (AUEB). The application enables the management of students, teachers, and courses, offering full CRUD functionality.

## Tech Stack
- Language: Java 21 (LTS)
- Framework: Spring Boot 3.5.x
- Security: Spring Security (Authentication & Authorization)
- Database: MySQL
- Database Migration: Flyway
- View Engine: Thymeleaf
- Build Tool: Gradle

## Architecture
The project follows the Layered Architecture pattern for maximum scalability and code maintainability:
- Controller Layer: Handles HTTP requests and data flow.
- Service Layer: Implements business logic and data processing.
- Repository Layer: Manages database communication via Spring Data JPA.
- DTOs & Mappers: Ensures secure data transfer between layers.

## Key Features
- CRUD Operations: Full management of users (Students/Teachers).
- Validation: Input data validation and error handling.
- JPA Auditing: Automatic tracking of record creation and modification dates.
- Security: Protected endpoints and user authentication system.

## Getting Started
1. Clone the repository.
2. Configure your MySQL connection in src/main/resources/application.properties.
3. Run the application using the Gradle Wrapper: ./gradlew bootRun
