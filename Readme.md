## Group 15 - Team Members
    Faysal Mohamed Daahir C1210097
    Mohamed Baashi Adam C1210113
    Mohamed Abdulkadir Mohamud C1210107
    Mohamed Abdala Warsame C1211022

## Bakery Shop Management System

You can access the source code on GitHub here:
https://github.com/Faysal-Maxamed/Bakery-Manegment-System.git


## Overview
The Bakery Shop Management System is designed to help manage a bakery's products, inventory, suppliers, and sales efficiently. The system features a user-friendly interface and comprehensive functionality.

## Features
User Authentication:
Secure login and account management for users.
Product Management:
Add, update, view, and delete bakery products.
Stock Management:
Monitor and update product stock levels in real-time.
Supplier Management:
Maintain a list of suppliers with details for easy tracking.
Sales Management:
Record and manage sales transactions, including generating receipts.
Reports:
View sales reports for better decision-making and analysis.
System Structure
PHP Files: Core logic for operations (e.g., index.php, home.php, etc.).
CSS & JS: Styling and interactivity for a responsive user experience.
Assets: Images and fonts used in the user interface.
Database: MySQL database to store bakery data (products, sales, suppliers, etc.).

2. Create the Database
Open your MySQL interface (e.g., phpMyAdmin).
Create a new database (e.g., bakery_shop).
Manually create the necessary tables based on the fields used in the project files.
3. Configure Database Connection
Open the DBConnection.php file.
Update the database credentials to match your setup:
php
Copy code
$conn = new mysqli('localhost', 'root', '', 'bakery_shop');
4. Run the Application
Start your server (e.g., Apache in XAMPP).
Open your browser and navigate to http://localhost/bsms.
Usage
Accessing the System
Navigate to the login page (login.php).
Use predefined admin credentials or create a new account to log in.
Dashboard
Once logged in, you will be directed to the dashboard where you can:
Add new bakery products.
Update product stock levels.
Track and manage sales transactions.
View sales reports for business insights.
Contributions
