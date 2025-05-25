# 🛒 E-Commerce Website (Spring Boot + MySQL)

This is a full-featured E-Commerce web application built using **Spring Boot**, **Spring MVC**, **Spring Data JPA**, and **MySQL**. It enables users to browse products, add them to the cart, register/login, and place orders.

## ✨ Features

- User registration & login (Spring Security)
- Product listing & categorization
- Cart management
- Order placement
- Admin dashboard for managing products
- RESTful API integration
- Responsive frontend (Thymeleaf/React - optional)

## 🛠️ Tech Stack

- **Backend**: Java, Spring Boot, Spring Data JPA
- **Database**: MySQL
- **Frontend**: Thymeleaf / React (optional)
- **Security**: Spring Security, JWT (optional)
- **Tools**: Maven, STS (Spring Tool Suite), Postman

## 💾 Database Setup

1. Create a MySQL database named `ecommerce`.
2. Update your `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
   spring.datasource.username=root
   spring.datasource.password=yourpassword
