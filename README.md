# 5COSC019W — Tutorial 1: Products API

**Student:** W.S.M.J. Abeysingha  
**University of Westminster ID:** w2182055  
**IIT student ID:** 20241893  
**Module:** 5COSC019W Object Oriented Programming

## Project overview
This Spring Boot project demonstrates basic REST endpoints, a JavaBean-style `Person` class, API documentation with Swagger UI, and source control with Git/GitHub.

## Requirements
- Java version compatible with the version configured in `pom.xml` (Java 25)
- IntelliJ IDEA
- Maven (the project includes the Maven Wrapper)

## Run the application
1. Open this project in IntelliJ IDEA by selecting its `pom.xml` or project folder.
2. Wait for Maven to load dependencies.
3. Run `ProductsApiApplication.java`.
4. Open the URLs below in your browser while the application is running.

## Endpoints
- `GET http://localhost:8080/hello` — returns `Hello from Spring Boot!`
- `GET http://localhost:8080/status` — returns the API status and current date
- `GET http://localhost:8080/goodbye` — returns `Goodbye from Spring Boot!`
- `GET http://localhost:8080/info` — optional additional information endpoint
- Swagger UI: `http://localhost:8080/swagger-ui.html`

## Person class
`Person` has `name` and `email` fields, getters and setters, a no-argument constructor, and constructors for name or name plus email.

## Before submission
Run the application and verify the required endpoints and Swagger UI on your own computer. Then create your own GitHub repository, push this project to it, and submit that repository URL through Blackboard.
