# Springboot-app
spring boot app for an automobile register.
This a Spring Boot web application that provides user login and registration functionality,and executes the CRUD operations on a table from 
an PHPmyadmin database.
It uses:
Thymeleaf for the frontend templates
Spring Data JPA to interact with a MySQL database which is created in phpMyadmin.
A Utilizator entity to represent users(username+password).
A Masina entity to represent the cars from db.
A custom /login endpoint that handles both login and registration based on a form action
A password encryption using Sha-256 algorithm.
