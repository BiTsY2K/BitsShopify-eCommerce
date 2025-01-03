# **BitsShopify - E-commerce Backend**
Welcome to **Bits-Shopify**, a simple and robust Spring Boot-powered backend application designed for e-commerce platforms. This project provides the foundational services required for managing users, products, and orders, with features like security, validation, and seamless database integration.

## Key Features
   * **User Authentication & Authorization:** Secured endpoints using Spring Security and JWT (JSON Web Tokens).
   * **Database Integration:** Fully integrated with MySQL using JPA for ORM (Object Relational Mapping).
   * **API Validation:** Ensures data integrity using Spring Boot Validation.
   * **Model Mapping:** Simplified DTO mapping using ModelMapper.

## Built With
   * **Spring Boot** - Core framework for the backend.
   * **MySQL** - Database for persistent data storage.
   * **Spring Data JPA** - ORM to interact with the database.
   * **Spring Security** - Secures API endpoints.
   * **JWT (io.jsonwebtoken)** - Token-based authentication.
   * **ModelMapper** - Simplifies DTO conversion.
   * **Lombok** - Reduces boilerplate code.

## Prerequisites
Ensure you have the following installed:
   * Java 18+
   * Maven 3.6+
   * MySQL 8.0+
   * Visual Studio Code with the following extensions:
      * Spring Boot Extension Pack
      * Java Extension Pack
      * Debugger for Java
   * Postman [For testing API (Optional)]

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/bits-shopify.git
   cd bits-shopify
   ```
2. **Configure MySQL:**
   - Create a new MySQL database:
      ```sql
      CREATE DATABASE bits_shopify;
      ```
   - Update the `application.properties` file with your MySQL credentials
      ```properties
      spring.datasource.url=jdbc:mysql://localhost:3306/bits_shopify_db
      spring.datasource.username=your_username
      spring.datasource.password=your_password
      ```
3. **Open the Project in VS Code:**
   - Open Visual Studio Code.
   - Use the "Open Folder" option to navigate to the bits-shopify directory.
   - Wait for VS Code to detect the Maven project and load dependencies.

4. **Build the application:**
   - Open the integrated terminal in VS Code (`` Ctrl+` `` on Windows/Linux or `` Cmd+` ``  on macOS).
   - Run:
      ```bash
      mvn clean install
      ```
5. **Run the application:**
   - Press F5 in VS Code to start debugging, or use the terminal:
      ```bash
      mvn spring-boot:run
      ```
6. **Access the API:** 
   - Open your browser or API client (e.g., Postman) and navigate to:
      ```bash
      http://localhost:3000/api/v1
      ```
      
