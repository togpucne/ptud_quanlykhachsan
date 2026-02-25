# Toa Sang Resort Management System

A web-based Resort Management Information System developed using PHP (MVC architecture), MySQL, Bootstrap, and JavaScript.

This project simulates real-world resort operations including room booking, role-based administration, promotion management, and mock online payment integration.

## System Architecture

The system follows the **Model–View–Controller (MVC)** pattern to ensure separation of concerns and maintainability.

```
ABC-RESORT/
│
├── client/
│   ├── model/
│   ├── view/
│   ├── controller/
│   └── index.php
│
├── server/
│   ├── model/
│   ├── view/
│   ├── controller/
│
└── Database: MySQL
```

- **Client** → Customer-facing booking system
- **Server** → Administrative management system
- **Database** → Relational data storage using MySQL

## Key Features

- Room search and booking workflow
- Dynamic guest information handling
- Promotion validation (amount-based & night-based)
- Cash & Mock MoMo payment integration
- Role-Based Access Control (6 actors)
- Booking history tracking
- Revenue and operational management

## Local Access (XAMPP)

After starting Apache and MySQL:

**Customer Interface:**

```
http://localhost/ABC-Resort/client/index.php
```

**Admin Login:**

```
http://localhost/ABC-Resort/server/view/login/login.php
```

## Technologies Used

**Backend**

- PHP (Core MVC structure)
- MySQL
- XAMPP

**Frontend**

- HTML5
- CSS3
- Bootstrap
- JavaScript
- Font Awesome

## Installation

1. Clone the repository
2. Move project to `htdocs/` (XAMPP)
3. Import the database via phpMyAdmin
4. Start Apache & MySQL
5. Access via the URLs above

## Author

Nguyen Trong Phuc
Information Systems Student
Industrial University of Ho Chi Minh City
