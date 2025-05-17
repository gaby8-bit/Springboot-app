# Springboot-app

Spring Boot app for an automobile register.

This is a Spring Boot web application that:
- Provides user login and registration functionality.
- Executes CRUD operations on a table from a PHPMyAdmin database.
- Uses **Thymeleaf** for the frontend templates.
- Uses **Spring Data JPA** to interact with a MySQL database (created in PHPMyAdmin).
- Defines a `Utilizator` entity (username + password).
- Defines a `Masina` entity to represent the cars.
- Includes a custom `/login` endpoint that handles both login and registration via form action.
- Encrypts passwords using the **SHA-256** algorithm.

