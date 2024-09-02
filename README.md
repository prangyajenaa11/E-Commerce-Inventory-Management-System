# E-commerce Inventory Management System

## Overview
This E-commerce Inventory Management System is a robust Java-based application designed to help online businesses efficiently manage their product inventory. It provides a user-friendly interface for tracking stock levels, managing product information, and generating reports.

## Features
- Real-time inventory tracking
- Product management (add, edit, delete)
- Stock level alerts
- Order management
- Supplier management
- Inventory reports generation
- User authentication and authorization

## Technologies Used
- **Frontend**: Java Swing
- **Backend**: Java
- **Database**: MySQL

## Prerequisites
- Java Development Kit (JDK) 8 or higher
- MySQL 5.7 or higher
- Maven (for dependency management)

## Setup Instructions

### 1. Clone the repository
```
git clone https://github.com/your-username/ecommerce-inventory-management.git
cd ecommerce-inventory-management
```

### 2. Database Setup
- Create a MySQL database named `ecommerce_inventory`
- Update the database configuration in `src/main/resources/config.properties` with your MySQL credentials

### 3. Build the project
```
mvn clean install
```

### 4. Run the application
```
java -jar target/ecommerce-inventory-management-1.0-SNAPSHOT.jar
```

## Usage Guide
1. Launch the application
2. Log in with your credentials (default admin: username `admin`, password `admin123`)
3. Use the menu to navigate between different modules:
   - Inventory: Add, edit, or remove products
   - Orders: Manage customer orders
   - Suppliers: Manage supplier information
   - Reports: Generate inventory reports


