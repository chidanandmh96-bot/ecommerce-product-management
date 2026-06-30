# E-Commerce Product Management System

## 📌 Project Overview

This is a simple Spring Boot REST API project for managing products. It performs CRUD (Create, Read, Update, Delete) operations using Spring Boot, Spring Data JPA, Hibernate, and PostgreSQL.

## 🚀 Technologies Used

- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- PostgreSQL
- Maven
- REST API
- Postman
- Git & GitHub

## 📂 Project Structure

```
src
 ├── controller
 │      ProductController.java
 ├── entity
 │      Product.java
 ├── repository
 │      ProductRepository.java
 ├── service
 │      ProductService.java
 ├── service/impl
 │      ProductServiceImpl.java
 ├── EcommerceApplication.java
 └── resources
        application.properties
```

## 📌 REST APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /products | Add Product |
| GET | /products | Get All Products |
| GET | /products/{id} | Get Product By ID |
| PUT | /products/{id} | Update Product |
| DELETE | /products/{id} | Delete Product |

## 📌 Features

- Add Product
- View All Products
- View Product By ID
- Update Product
- Delete Product
- Layered Architecture
- PostgreSQL Database Integration

## 🛠 Database

Database Name:

```
ecommerce
```

## ▶ Run the Project

1. Create PostgreSQL database named `ecommerce`.
2. Update `application.properties` with your PostgreSQL username and password.
3. Run `EcommerceApplication.java`.
4. Test APIs using Postman.

## 👨‍💻 Author

**Chidanand M H**
