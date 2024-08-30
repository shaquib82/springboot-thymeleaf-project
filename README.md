# Spring Boot Thymeleaf Project

## Description

This project is a Spring Boot application using Thymeleaf for templating. It serves as an example of integrating Spring Boot with Thymeleaf to build a web application that manages employee information.

## Features

- **Employee Directory**: View, add, update, and delete employee records.
- **Bootstrap Integration**: Utilizes Bootstrap for styling.
- **JPA Integration**: Uses Spring Data JPA for data persistence with a MySQL database.

## Getting Started

### Prerequisites

- **Java**: Ensure you have Java 17 installed.
- **Maven**: Make sure Maven is installed for dependency management.
- **MySQL**: Have MySQL installed and running.

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/shaquib82/springboot-thymeleaf-project.git

2. Navigate to Project Directory
   cd springboot-thymeleaf-project

3. Update Application Properties
   Modify the src/main/resources/application.properties file with your MySQL database configuration.
   spring.datasource.url=jdbc:mysql://localhost:3306/employee_directory
   spring.datasource.username=your_username
   spring.datasource.password=your_password

4. Run the Application
   Use Maven to build and run the application: ./mvnw spring-boot:run

5. Access the Application
   Open your browser and go to http://localhost:8080.


### Usage
- View Employees: Navigate to /employees/list to see the list of employees.
- Add Employee: Go to /employees/showFormForAdd to add a new employee.
- Update Employee: Use /employees/showFormForUpdate/{id} to update an existing employee.
- Delete Employee: Click on the delete button next to an employee in the list to remove them.
- 
### Contributing

- Fork the Repository: Create your own fork of the repository.
- Clone Your Fork: Clone your fork to your local machine.
- Create a Branch: Create a new branch for your changes.
- Commit Changes: Commit your changes with clear messages.
- Push Changes: Push your changes to your forked repository.
- Create a Pull Request: Open a pull request to the original repository.

### License
This project is licensed under the MIT License. See the LICENSE file for details.


