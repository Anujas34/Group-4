# Customer Service Management System

## Overview
A Java console application for managing customer inquiries, complaints, and resolutions for a consumer electronics company. This application uses Core Java and MySQL with JDBC for database interactions.

## Features
- Record, view, update, and delete inquiries and complaints
- Provide, view, update, and delete resolutions
- Manage customer data

## Getting Started

### Prerequisites
- Java JDK 11 or higher
- MySQL Server
- Maven (for dependency management)

### Setup

3.⁠ ⁠Set up the database:
    - Import the ⁠ customer_database.sql ⁠ file into your MySQL database to create the necessary tables.
4.⁠ ⁠Update database connection details:
    - Edit the ⁠ jdbc.properties ⁠ file in the ⁠ resources ⁠ directory with your database connection details.
5.⁠ ⁠Compile and run the application:
    - Use your preferred IDE or run the following command:
    ⁠ bash
    javac -d bin src/main/java/*.java
    java -cp bin Main
     ⁠

## Usage Instructions
1.⁠ ⁠Run the application.
2.⁠ ⁠Follow the on-screen menu to manage donors, inventory, and requests.

## License
This project is licensed under the MIT License
