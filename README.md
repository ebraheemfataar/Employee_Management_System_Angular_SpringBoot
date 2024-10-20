# Employee Management System With Angular SpringBoot

![alt text](image.png)

## Overview

The **Employee Management System** is a web application designed to manage employee records efficiently. This application utilizes **Angular 18** for the frontend and **Spring Boot** for the backend, with **MySQL** as the database.

## Tech Stack

- **Frontend**: Angular 18
- **Backend**: Spring Boot
- **Database**: MySQL Workbench
- **Reference Repository**: [GitHub Repository](https://github.com/RameshMF/Angular-10-Spring-Boot-CRUD-Full-Stack-App)
- **Video Tutorial**: [YouTube Playlist](https://www.youtube.com/playlist?list=PLGRDMO4rOGcPr9SapBV8NbD9eHAiaTDMl)

## Features

- **Employee List**: View all employees with their details.
- **Add Employee**: Add new employee records.
- **Update Employee**: Modify existing employee information.
- **Delete Employee**: Remove employee records from the system.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 11 or later
- Apache Maven
- MySQL Workbench
- Node.js and npm (for Angular)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ebraheemfataar/Employee_Management_System_Angular_SpringBoot.git
   ```

## Backend Setup

1. **Navigate to the backend folder**:
   ```bash
   cd api
   ```
2. Configure your MySQL database in the **application.properties** file.

3. Build and run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

The backend server will run on http://localhost:8080.

## Frontend Setup

1. Navigate to the frontend folder:

   ```bash
   cd app
   ```

2. Install the Angular dependencies:

   ```bash
   npm install
   ```

3. Run the Angular application:
   ```bash
   ng serve
   ```

The frontend will be accessible at http://localhost:4200.

## API Endpoints

- GET /api/v1/employees: Retrieve the list of employees.
- POST /api/v1/employees: Add a new employee.
- GET /api/v1/employees/{id}: Retrieve an employee by ID.
- PUT /api/v1/employees/{id}: Update an existing employee.
- DELETE /api/v1/employees/{id}: Delete an employee.

## CORS Configuration

CORS is configured to allow requests from the Angular frontend. The backend allows access from http://localhost:4200.
