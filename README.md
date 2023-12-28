Java JDBC CRUD Application with MySQL

Project Overview:
This project is a Java application that demonstrates the implementation of a simple CRUD (Create, Read, Update, Delete) functionality using JDBC (Java Database Connectivity) to interact with a MySQL database. The application focuses on managing information about sellers and departments in a relational database.

Technologies Used:

Java: Core programming language.
JDBC: Java Database Connectivity for interacting with the MySQL database.
MySQL: Relational database management system.
Maven: Dependency management and project build tool.
Git: Version control system.
IDE: Developed using an Integrated Development Environment (IDE) such as Eclipse or IntelliJ.

Project Structure:

The project is structured as follows:

src/: Contains the source code for the application.
application/: Main application classes.
db/: Database-related utility classes.
model/: Entity classes representing sellers and departments.
model/dao/: Data Access Object interfaces and implementations.
resources/: Contains resource files, such as database configuration properties.
pom.xml: Maven project configuration file.

Functionality:

Seller Management:

Retrieve a seller by ID.
Retrieve sellers by department.
Retrieve all sellers.
Insert a new seller.
Update an existing seller.
Delete a seller by ID.

Department Management:

Retrieve a department by ID.
Retrieve all departments.
Insert a new department.
Update an existing department.
Delete a department by ID.

Usage:

Database Configuration:

Ensure that the MySQL database is set up.
Configure the database connection properties in the resources/db.properties file.

Building the Project:

Use Maven to build the project and manage dependencies.
Running the Application:

Execute the Program.java and DepartmentProgram.java files in the application package to perform various CRUD operations.

How to Run:

Clone the repository to your local machine using git clone.
Configure your MySQL database connection details in resources/db.properties.
Build the project using Maven (mvn clean install).
Run Program.java and DepartmentProgram.java to interact with the application.

Contributions:

Contributions to enhance the project or address issues are welcome. Feel free to create pull requests or open issues.

Author:

Anderson Pyetro
Instagram: instagram.com/@apyetro

License:

This project is licensed under the MIT License.
