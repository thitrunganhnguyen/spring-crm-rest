# Customer Relationship Management (CRM) System REST API

This project is a practical implementation of the tutorial "Spring and Hibernate for Beginners (Includes Spring Boot)" available on Udemy. It creates a REST API for a Customer Relationship Management system, allowing REST clients to perform various actions on customer data.

## Project Overview

In this project, we utilize the power of Spring REST and Hibernate to develop a comprehensive REST API that offers a range of functionalities to interact with customer information. The API enables clients to seamlessly perform actions such as retrieving customer lists, accessing individual customer details, adding new customers, updating existing customer records, and even deleting customer entries.

## Features

- Get a list of customers
- Get a single customer by ID
- Add a new customer
- Update an existing customer
- Delete a customer

## API Endpoints and HTTP Methods

- `GET /api/customers`: Retrieve a list of all customers.
- `GET /api/customers/{customerId}`: Retrieve information about a specific customer by ID.
- `POST /api/customers`: Create a new customer.
- `PUT /api/customers/{customerId}`: Update an existing customer's information.
- `DELETE /api/customers/{customerId}`: Delete a customer.

## Usage

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your-username/your-project.git
2. Configuring the MySQL Database: The CRM System REST API employs a MySQL database to efficiently manage customer data. To seamlessly integrate the MySQL database with the CRM System REST API, ensure your MySQL connection details are accurately set in the existing `src/main/resources/persistence-mysql.properties` file. Adjust the `jdbc.url`, `jdbc.username`, and `jdbc.password` parameters to align with your MySQL configuration. Customization options, including character encoding and connection pooling, can be tailored as required.

3. Build and Run: Build and run the application using Maven.

4. Access the API: Interact with the API using your preferred REST client or tools.

## Exception Handling
This project includes robust exception handling to provide meaningful error messages and responses in case of unexpected scenarios.

## Credits
This project was developed based on the tutorial "Spring and Hibernate for Beginners (Includes Spring Boot)" on Udemy.
