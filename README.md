# Student Management System - Java Full Stack

## Technologies
- Java 17
- Spring Boot
- Spring JDBC
- MySQL
- HTML
- CSS
- JavaScript
- Maven

## Setup

1. Install Java 17+, Maven, and MySQL.
2. Run `database.sql` in MySQL.
3. Open `src/main/resources/application.properties`.
4. Replace `YOUR_MYSQL_PASSWORD` with your MySQL password.
5. From the project folder run:

   mvn spring-boot:run

6. Open:

   http://localhost:8080

## Features
- Add student
- View students
- Update student
- Delete student

## Architecture

Browser
  -> HTML/CSS/JavaScript
  -> Spring Boot REST Controller
  -> JDBC Repository
  -> MySQL
