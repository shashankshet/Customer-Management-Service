# Customer Management System

This is a simple Customer Management System built with React, Spring Boot, and PostgreSQL.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
  - [Frontend Setup](#frontend-setup)
  - [Backend Setup](#backend-setup)
  - [Database Setup](#database-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Customer Management System is designed to perform CRUD operations on customer records. It consists of a React front-end for the user interface, a Spring Boot backend for handling business logic, and a PostgreSQL database for storing customer data.

## Technologies Used

- **Frontend:**
  - React
  - Axios (HTTP client)

- **Backend:**
  - Spring Boot
  - Spring Data JPA
  - PostgreSQL
  - Maven

- **Database:**
  - PostgreSQL

## Setup

### Frontend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/customer-management-system-frontend.git
   cd customer-management-system-frontend

2. Install dependencies:
```bash
npm install
```
Run the application:
```bash
npm start
```
The app will be accessible at http://localhost:3000.

### Backend Setup
Clone the repository:
```bash
git clone https://github.com/your-username/customer-management-system-backend.git
cd customer-management-system-backend
```
Open the project in your preferred IDE (Eclipse, IntelliJ, etc.).

Configure the database connection in src/main/resources/application.properties.

Run the Spring Boot application.

The backend will be accessible at http://localhost:8080.

### Database Setup
Install PostgreSQL.

Create a database named customer_management_system.

Update the database configuration in the backend application.properties file.

Run the Spring Boot application to initialize the database schema.

### Usage
Access the React frontend at http://localhost:3000 to perform CRUD operations on customer records.
Contributing
If you'd like to contribute to this project, please follow the Contributing Guidelines.

### License
This project is licensed under the MIT License.
