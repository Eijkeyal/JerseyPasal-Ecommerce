# JerseyPasal ⚽👕

JerseyPasal is a full-stack e-commerce web application developed for football jersey enthusiasts. The platform allows users to browse, purchase, review, and manage football jerseys while providing administrators with powerful tools to manage products, users, orders, and business operations.

## 📌 Project Overview

JerseyPasal is a Java-based web application developed using JSP, Jakarta Servlets, Maven, and MySQL following the MVC (Model-View-Controller) architecture. The system provides a complete online shopping experience for football jerseys, including authentication, shopping cart management, wishlist functionality, payment processing, order tracking, and administrative management.

---

## 🚀 Features

### Customer Features

* User Registration with Profile Image Upload
* Secure Login System
* Admin Account Approval
* Browse Club Jerseys
* Browse National Team Jerseys
* Product Search Functionality
* Product Filtering
* Product Detail Pages
* Add to Cart
* Wishlist Management
* Buy Now Option
* Payment Processing
* Order Tracking
* User Dashboard
* Profile Management
* Product Reviews and Ratings
* Contact Support Form

### Admin Features

* Admin Dashboard
* User Approval & Denial System
* Product Management (Add/Edit/Delete)
* Order Management
* Order Status Updates
* Customer Message Management
* Revenue Monitoring
* Stock Monitoring
* Most Ordered Product Analytics
* Low Stock Product Reporting

---

## 🛠️ Technology Stack

### Backend

* Java
* Jakarta Servlets
* JSP (Java Server Pages)
* Maven

### Frontend

* HTML5
* CSS3
* JavaScript

### Database

* MySQL

### Architecture

* MVC (Model-View-Controller)

### Development Tools

* Apache Tomcat
* MySQL Workbench
* Eclipse IDE

---

## 🏗️ System Architecture

The project follows the MVC architecture:

### Model Layer

Contains Java model classes representing:

* Users
* Products
* Orders
* Payments
* Reviews
* Wishlist
* Cart

### View Layer

Implemented using:

* JSP Pages
* HTML
* CSS
* JavaScript

### Controller Layer

Implemented using:

* Jakarta Servlets

### Data Access Layer

Implemented using:

* DAO Classes
* JDBC
* MySQL

---

## 🔐 Security Features

* Password Hashing
* Session Management
* Authentication Filters
* Authorization Filters
* Role-Based Access Control
* Admin Approval Workflow
* Protected Routes
* Backend Form Validation
* SQL Injection Prevention using Prepared Statements
* Custom Error Pages

---

## 🗄️ Database Design

### Main Tables

* users
* products
* cart
* cart_items
* wishlist
* orders
* order_items
* payments
* reviews
* contact_messages

The database is normalized up to Third Normal Form (3NF) to reduce redundancy and maintain data integrity.

---

## 📦 Core Modules

### User Management

* Registration
* Login
* Profile Management
* Account Approval

### Product Management

* Product Listing
* Product Details
* Product Search
* Product Filters
* Product CRUD Operations

### Shopping System

* Cart Management
* Wishlist Management
* Checkout Process
* Payment Handling

### Order Management

* Place Orders
* View Orders
* Update Order Status
* Track Deliveries

### Review System

* Product Ratings
* Customer Reviews

### Contact System

* Customer Enquiries
* Admin Message Management

---

## 📂 Project Structure

```text
src/
│
├── controller/
│   ├── servlet/
│   ├── dao/
│   ├── model/
│   ├── filter/
│   ├── service/
│   └── utils/
│
├── webapp/
│   ├── WEB-INF/
│   ├── assets/
│   ├── css/
│   ├── images/
│   ├── js/
│   └── jsp/
│
└── pom.xml
```

---

## ⚙️ Installation Guide

### Prerequisites

* Java JDK 17+
* Apache Tomcat 10+
* Maven
* MySQL Server

### Clone Repository

```bash
git clone https://github.com/pankajrai144/JerseyPasal.git
cd JerseyPasal
```

### Database Setup

1. Create a MySQL database:

```sql
CREATE DATABASE JerseyPasal;
```

2. Import the provided SQL file.

3. Update database credentials inside:

```java
DBconfig.java
```

```java
private static final String URL = "jdbc:mysql://localhost:3316/JerseyPasal";
private static final String USER = "root";
private static final String PASSWORD = "";
```

### Build Project

```bash
mvn clean install
```

### Deploy

Deploy the generated WAR file to Apache Tomcat.

---

## 🧪 Testing

The project includes extensive testing for:

* Registration Validation
* Login Functionality
* Payment System
* Cart Operations
* Wishlist Operations
* Profile Management
* Order Processing
* Product Reviews
* Search Functionality
* Product Filtering
* Admin Operations

---

## 📈 Future Enhancements

* Online Payment Gateway Integration (eSewa/Khalti)
* Email Verification
* Password Reset System
* Product Recommendations
* AI Chat Support
* Mobile Responsive Improvements
* REST API Development
* Spring Boot Migration
* JWT Authentication
* Cloud Deployment

---

## 👥 Team Members

| Name                 | 
| -------------------- | 
| Pankaj Rai           | 
| Eijkeyal Pakhrin     | 
| Bishrut Raj Adhikari | 
| Manisha Shah         | 
| Kritee Khadka        | 
### ⭐ If you found this project useful, consider giving it a star on GitHub!
