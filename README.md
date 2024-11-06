# Java Full Stack Task: Role-Based Authentication Module - Backend

## Overview
This backend module is part of a Role-Based Authentication (RBAC) system using Spring Boot.

## Features
- JWT-based authentication
- User registration and login
- Role-based access control (Admin and User)
- Secure endpoints for different user roles


## Installation
### Prerequisites
1. Install Visual Studio Code from >> https://code.visualstudio.com/download
2. Install  Java - jdk17  from  >> https://www.oracle.com/in/java/technologies/downloads
3. Install MYSQL server for Database from >> https://www.mysql.com/downloads
make sure all the above installations are installed properly.

### To set up the project locally:
- Clone the repository.                         
-  git clone https://github.com/your-username/repository-name.git
-  cd repository-name
-  git checkout backend
-  Navigate to the backend directory.

### Install dependencies :
- Go to >> https://start.spring.io/ website and add the dependencies follows:
- Spring WEb
- Spring Data JPA
- Spring Security
- Spring Boot Dev tools
- MySQL Driver

# Usage : 
## Project Structure:
- src
- main
- java
- com
- example
- OJT
- OjtApplication.java                       // main  method class
- config >> AppConfig.java
          >> SecurityConfig.java                  // Spring Security configuration
          >> WebSecurityConfigurerAdapter.java
- controllers >> UserController.java                  // REST controller for authentication
- models >> User.java                            // User entity
- repository >>  UserRepository.java          // User repository interface
- service >> UserService.java             // User service class
- utils >> JwtUtil.java                 // JWT utility class
- filter >> JwtAuthenticationFilter.java   
- resources >> application.properties   
- By using this project structure  develop the backend application
- Run the OjtApplication.java file, the Spring Boot application will starts.

  
# Environment Variables:
- DATABASE_URL= jdbc:mysql://localhost:3306/rbac_db
- JWT_SECRET= sS0RJc6PNefnp+2awVYXxYNnDW2EAwavBO4ZCRCJEX4=

# Testing:
- For testing purpose install Postman API from >> https://www.postman.com/downloads
- Give the backend API credentials that are given in UserController.java.
- Navigate to those End Points where the login and register pages works.
- Give the data in json format and send the request it will return the response.

# Deployment:
- To deploy the Spring Boot application, consider using platforms like Heroku, Render, or AWS. 
- Ensure your application is configured for production, including environment variables and database connections.

# Contributions:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Commit your changes and push to your branch.
- Create a pull request detailing your changes.

# License:
This project is licensed under the MIT License.


   

