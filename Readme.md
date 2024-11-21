# Category&Product Management API Project:

This is a Spring Boot project demonstrating a RESTful API for managing categories and products, with a MySQL database integration.

## Features:
- CRUD operations for Categories.
- CRUD operations for Products.
- Relational mapping between categories and products.
- Integration with MySQL database.
- API tested using Postman.

## Prerequisites:
- Before running the application, ensure you have:
- Java Development Kit (JDK): Version 17 or higher.
- Maven: For building the project.
- MySQL: For database integration.
- Postman (optional): For API testing.


## Database Configuration:
#### This project uses MySQL as the database. Update your database credentials in application.properties:
- spring.datasource.url=jdbc:mysql://<host>:<port>/<database_name>
- spring.datasource.username=<username>
- spring.datasource.password=<password>
- spring.jpa.hibernate.ddl-auto=update

#### To connect to a remote MySQL database (example configuration):
- spring.datasource.url=jdbc:mysql://sql12.freesqldatabase.com:3306/sql12746122
- spring.datasource.username=sql12746122
- spring.datasource.password=dDVGg6hXYt