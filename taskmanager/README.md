# Task Manager API

A RESTful web service built with Java and Spring Boot that demonstrates
Object Oriented Programming (OOP) principles connected to a SQL database.

## Technologies Used
- Java 25
- Spring Boot 4.1.1
- Spring Data JPA (ORM)
- H2 Database
- Maven

## Project Architecture
This project follows a 3-layer architecture:
- **Model** - Task.java maps a Java class to a SQL table using JPA
- **Repository** - TaskRepository.java handles all SQL operations
- **Controller** - TaskController.java handles all HTTP web requests

## API Endpoints
| Method | URL | Description |
|--------|-----|-------------|
| GET | /tasks | Returns all tasks |
| POST | /tasks | Creates a new task |

## How to Run
1. Clone the repository
2. Navigate to the project folder
3. Run: ./mvnw spring-boot:run
4. Visit: http://localhost:8080/tasks

## Database Console
Visit http://localhost:8080/h2-console to view the live SQL database.
- JDBC URL: jdbc:h2:mem:taskdb
- Username: sa
- Password: (empty)

## OOP Concepts Demonstrated
- Encapsulation (private fields with getters/setters)
- Annotations (@Entity, @RestController, @GetMapping)
- Interfaces (JpaRepository)
- Constructor injection (TaskController)

## Author
Triron James | Computer Science Student
Built as a portfolio project demonstrating Java OOP + SQL integration