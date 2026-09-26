# Apartment Visitors Management System
 
## Project Overview
The Apartment Visitors Management System (AVMS) is a web-based PHP and MySQL
application designed to manage visitor records in an apartment environment.
 
The system provides an administrator interface for registering visitors,
viewing visitor details, recording visitor exits, searching visitors,
managing visitor categories, creating visitor passes, managing passes,
and generating date-based visitor and pass reports.
 
## Technology Stack
- PHP
- MySQL
- HTML5
- CSS3
- JavaScript
- jQuery
- Bootstrap 4.1
- Chart.js
- Font Awesome
- XAMPP
- VS Code
 
## Project Structure
AVMS-Project-PHP/
├── avms/
│   ├── index.php
│   ├── dashboard.php
│   ├── visitors-form.php
│   ├── manage-newvisitors.php
│   ├── visitor-detail.php
│   ├── search-visitor.php
│   ├── category.php
│   ├── create-pass.php
│   ├── manage-passes.php
│   ├── pass-details.php
│   ├── bwdates-reports.php
│   ├── bwdates-reports-details.php
│   ├── bwdates-passreports.php
│   ├── bwdates-passreports-details.php
│   ├── admin-profile.php
│   ├── change-password.php
│   ├── forgot-password.php
│   ├── resetpassword.php
│   ├── logout.php
│   ├── includes/
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── fonts/
│   └── vendor/
│
└── SQL File/
    └── avmsdb.sql
 
## Main Features
- Administrator login
- Dashboard
- Visitor registration
- Visitor management
- Visitor details
- Visitor exit tracking
- Visitor search
- Visitor category management
- Visitor pass creation
- Visitor pass management
- Date-based visitor reports
- Date-based visitor-pass reports
- Administrator profile
- Password change
- Password recovery/reset
- Logout
 
## Database
Database name: avmsdb
 
Main tables:
- tbladmin
- tblcategory
- tblvisitor
- tblvisitorpass
 
## Installation
1. Install XAMPP with Apache and MySQL.
2. Copy the avms folder into: C:\xampp\htdocs\
3. Start Apache and MySQL.
4. Open http://localhost/phpmyadmin and create a database named avmsdb.
5. Import SQL File/avmsdb.sql into the avmsdb database.
6. Open http://localhost/avms/
 
## Administrator Login
Use the administrator credentials configured in the supplied project/database.
 
## Reusable Components
The project uses reusable PHP include files:
- includes/header.php
- includes/sidebar.php
- includes/footer.php
- includes/dbconnection.php
 
These components provide common layout, navigation, footer, and database
connectivity functionality.
 
## Frontend Resources
- Bootstrap 4.1
- jQuery
- Chart.js
- Font Awesome
- Bootstrap Progress Bar
- Select2
- Datepicker and other supporting libraries
 
## Development Notes
The application follows a modular PHP page structure with reusable include
components. Visitor, pass, category, authentication, and reporting
functionality are separated into dedicated PHP pages.
 
Future improvements can include stronger password hashing, prepared SQL
statements, CSRF protection, additional user roles, API support,
notification functionality, and QR-based visitor verification.

How to run the Apartment Visitors Management System (AVMS) Project

1. Download the  zip file

2. Extract the file and copy avms folder

3.Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)

4. Open PHPMyAdmin (http://localhost/phpmyadmin)

5. Create a database with name avmsdb

6. Import avmsdb.sql file(given inside the zip package in SQL file folder)

7.Run the script http://localhost/avms (frontend)

Credential for admin panel :

Username: admin

Password: Test@123
