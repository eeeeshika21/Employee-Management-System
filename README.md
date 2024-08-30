# Employee Management System

This Employee Management System is a robust application designed to streamline the management of employee data and departmental information within an organization. Built using Spring Boot 3, Spring Data JPA, and Hibernate, this project demonstrates essential concepts such as dependency injection, entity management, and database interaction. The project is well-structured, with a clear separation of concerns, making it easy to maintain and extend.

## Features

### Employee and Department Management:
- **CRUD Operations**: Easily create, read, update, and delete employees and departments.
- **Relationship Management**: Maintain and manage relationships between employees and departments.

### Spring Data JPA and Hibernate:
- **Database Integration**: Utilize Spring Data JPA and Hibernate for seamless interaction with the database.
- **Entity Management**: Manage entities using the Jakarta Persistence API.

### RESTful API Endpoints:
- **CRUD Endpoints**: RESTful endpoints for performing CRUD operations on employees and departments.
- **Query Methods**: Filter and sort data using integrated query methods.

## Technologies Used
- **Spring Boot 3**
- **Spring Data JPA**
- **Hibernate**
- **Jakarta Persistence API**
- **H2 Database** (for testing purposes)
- **Maven** (for project management)

## Project Structure
employeemanagementsystem
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.example.employeemanagementsystem
│   │   │       ├── EmployeemanagementsystemApplication.java
│   │   │       ├── config
│   │   │       │   └── JpaAuditingConfig.java
│   │   │       ├── controller
│   │   │       │   ├── DepartmentController.java
│   │   │       │   └── EmployeeController.java
│   │   │       ├── dto
│   │   │       │   ├── DepartmentDTO.java
│   │   │       │   └── EmployeeDTO.java
│   │   │       ├── model
│   │   │       │   ├── Department.java
│   │   │       │   └── Employee.java
│   │   │       ├── projection
│   │   │       │   ├── DepartmentProjection.java
│   │   │       │   └── EmployeeProjection.java
│   │   │       ├── repository
│   │   │       │   ├── DepartmentRepository.java
│   │   │       │   └── EmployeeRepository.java
│   │   │       ├── service
│   │   │       │   ├── DepartmentService.java
│   │   │       │   └── EmployeeService.java
│   │   ├── resources
│   │   │   ├── templates
│   │   │   ├── application.properties
│   │   │   ├── data.sql
│   │   │   └── schema.sql
│   ├── test
│   │   └── java
│   │       └── com.example.employeemanagementsystem
├── target
│   ├── generated-sources/annotations
│   ├── generated-test-sources/test-annotations
├── .mvn
├── .vscode
├── .gitignore
├── HELP.md
├── mvnw
├── mvnw.cmd
└── pom.xml

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/employee-management-system.git
   cd employee-management-system
2. **Open the project in Visual Studio Code**.

   Run the project:

Use the built-in Spring Boot features to run the application directly from the IDE.

4. **Access the application**:

The REST API will be available at http://localhost:8080/.
