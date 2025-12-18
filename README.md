# Capstone 3 – EasyShop (Backend + Frontend)

A super cute Spring Boot e-commerce application designed for a soft, pink aesthetic. This project involved taking an existing Version of a website and fixing core bugs in the API while implementing administrative controls. This project serves as a general goods store (The Easy Shop) where I acted as a backend developer to refine and expand the server-side logic.

---

## Completed Features

Phase 1: Categories Management

### Controller Implementation:

* Wrote implementation code for methods in the CategoriesController and MySqlCategoriesDao
* Verified that the JSON for categories matches the required format including categoryId, name, and description.

Phase 2: Bug Squashing

* Identified and fixed bugs in the filter functionality that was returning incorrect results.
* Resolved a bug where updating a product caused duplicates in the database instead of modifying the existing record
* Revamped the existing CSS to create a cohesive pink brand identity for the storefront.

---

## API Testing (Insomnia)

I relied on insomnia to test my application endpoints and logic through the development process. 
I verified that searching by minPrice and maxPrice now returns the correct filtered data

---

## Core Technologies

* **Java and Spring Boot - Backend API framework**
* **MySQL - Data storage for users, products, and categories** (to run the database script)
* **CSS - Custom styling**

---

## Interesting Piece of code

I used CSS to give the product cards a soft glow and a "floating" effect when hovered over.

.product:hover {
transform: translateY(-5px);
box-shadow: 0 8px 15px rgba(255, 175, 204, 0.3);
border 2px: solid #ffc2d1:
}
---

## Database setup (MySQL)

1. Database: Execute "create_database.sql" in MySQL Workbench
2. API: Launch the Spring Boot Application

 