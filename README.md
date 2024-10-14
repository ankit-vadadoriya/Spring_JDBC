# Spring_JDBC

This is a basic Spring JDBC project that demonstrates how to integrate JDBC with Spring for database interactions. The application allows managing student data in a relational database.

## Features

- Add, update, and retrieve student information from the database.
- Uses Spring JDBC for database operations.
- Includes schema and data setup scripts (`schema.sql` and `data.sql`).
- Follows a typical layered architecture (Model, Repository, Service).

## Project Structure

- **Main Class:** `SpringJdbcApplication.java` - Entry point for the Spring Boot application.
- **Model Class:** `Student.java` - Represents the student entity.
- **Repository:** `StudentRepo.java` - Data access layer using Spring JDBC.
- **Service:** `StudentService.java` - Contains the business logic.
