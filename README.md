# PHP-Internship-Task
# User Registration and Login System

This is a basic user registration and login system implemented using PHP and MySQL. The system allows users to register with their information and login using their credentials.

## Features

- User registration with Name, Email, Password, Address, and Phone Number fields.
- User login with email and password validation.
- Responsive user interface for both registration and login pages.
- Utilizes PHP-MySQLi for database interactions.

## Requirements

- PHP (>= 7.0)
- MySQL database server

## Installation and Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/user-registration-login.git


**Configure the Database:**
Create a MySQL database and import the provided SQL schema from database-schema.sql (if provided).

**Update Database Connection:**
Open the config.php file and update the database credentials (username, password, dbname) to match your MySQL setup.


**Launch your local development server:**
If using XAMPP/WAMP, place the project folder in the appropriate directory (e.g., htdocs) and access it via http://localhost/user-registration-login.

**Register a User:**
Access the registration page (registration.php) through your web browser and fill out the registration form.

**Login:**
Access the login page (login.php) through your web browser and enter the registered email and password to log in.
