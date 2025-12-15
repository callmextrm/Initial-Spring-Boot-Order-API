# Order Management API

A Spring Boot REST API for managing orders with a strict status lifecycle and business rules.

This project was built to practice real-world backend development using clean architecture and domain-driven logic.

---

## 🚀 Features

- Create, retrieve, update, and delete orders
- Enforced order status lifecycle
- Business rules validation in service layer
- RESTful API design
- MySQL persistence using Spring Data JPA

---

## 🔄 Order Status Lifecycle

Orders follow a strict lifecycle:

CREATED → PAID → SHIPPED → DELIVERED

### Invalid actions:
- Skipping steps
- Going backwards
- Modifying a DELIVERED order

---

## 🛠 Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Maven

---

## 📌 API Endpoints

### Create Order
### Get Orders
### Get Order by ID
### Update Order Status
### Delete order by ID

