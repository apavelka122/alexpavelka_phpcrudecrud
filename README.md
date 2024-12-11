# INET4031 PHP Crude CRUD App (MariaDB/MySQL Version)
## Overview
This project demonstrates a foundational dynamic data-driven web application using PHP and MariaDB/MySQL. While simple in implementation, it serves as an excellent starting point for understanding the principles behind web development with dynamic HTML and backend database interaction.

By mastering the mechanics of this app, you’ll gain insights that can be applied to more modern and advanced web development frameworks.

## Features
Basic CRUD (Create, Read, Update, Delete) functionality for managing data.
PHP-based dynamic HTML rendering.
Integration with MariaDB/MySQL for persistent data storage.
## Prerequisites
A MySQL/MariaDB database setup with a preconfigured employees database and user accounts.
Basic knowledge of PHP and SQL.
A web server configured to execute PHP scripts (e.g., Apache with PHP module or XAMPP).
## Setup
Database Configuration:
Ensure your MySQL/MariaDB database has the required schema and user accounts. Details about setting up the database will be provided during class sessions.

Modify credentials.php:
Update the credentials.php file with the appropriate database connection parameters (e.g., host, username, password, and database name).
Important: Replace the default credentials with your own secure values.

Deploy Files:
Place all files in a directory accessible by your web server (e.g., under htdocs for XAMPP or /var/www/html for Apache).

Access the Application:
Navigate to the appropriate URL in your web browser to interact with the app (e.g., http://localhost/inet4031-crud-app/).

## Security Notice
This app is intended for learning purposes and is not secure for production use.

Sensitive Information: Database credentials are stored in plain text and should be updated before deployment.
Lack of Security Measures: There are no protections against SQL injection, XSS, or other vulnerabilities.
For production applications, ensure secure practices such as input sanitization, prepared statements, and the use of environment variables for sensitive credentials.

## License
This project is provided for educational purposes as part of the INET4031 course curriculum.
