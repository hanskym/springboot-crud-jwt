# Learn Spring Boot

Spring Boot API for ecommerce with CRUD operations, JWT authentication, and PostgreSQL.

## Technologies Used

-   Java 17
-   Spring Boot 3.0.2
-   PostgreSQL
-   Lombok
-   JSON Web Token (JWT)
-   Swagger

## Dependencies

-   Spring Boot DevTools
-   Spring Boot Starter Data JPA
-   Spring Boot Starter Data JDBC
-   Spring Boot Starter Security
-   Spring Boot Starter Validation
-   Spring Boot Starter Web
-   PostgreSQL Driver
-   Lombok
-   JAXB API
-   JJWT for JWT handling
-   Springdoc OpenAPI for API documentation

## Installation

1. Prerequisites

    - Make sure Java Development Kit (JDK) version 17 or later is installed.
    - Verify that Maven is installed on your system. If it's not, you can download and install it from [Maven Apache](https://maven.apache.org/download.cgi).

2. Clone the Repository
    ```sh
    git clone https://github.com/hanskydev/learn-springboot-crud.git
    cd learn-springboot-crud
    ```
3. Database Configuration
   Update the `application.properties` file with your PostgreSQL database connection details:
    ```properties
    spring.datasource.url=jdbc:postgresql://localhost:5432/ecommerce
    spring.datasource.username=postgres
    spring.datasource.password=postgres
    ```
4. Open the project with your IDE, then build it using Maven:
    ```sh
    mvn clean install
    ```
5. Start the application with Maven after a successful build:
    ```sh
    mvn spring-boot:run
    ```
