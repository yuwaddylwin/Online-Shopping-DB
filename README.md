# E-Commerce Database System (SQL – Microsoft Access)

A scalable relational database system designed for an e-commerce platform, supporting customers, products, orders, and payments with optimized queries and normalized data structures.

---

## 📌 Overview
This project focuses on designing and implementing a structured SQL database to support core e-commerce operations.  
The system ensures data integrity, efficient querying, and scalability through proper normalization and indexing.

---

## 🛠️ Tech Stack
- Microsoft Access
- SQL 
- Relational Database Design

---

## 🧱 Database Design

### Core Entities
- **Customers** – customer details and contact information
- **Products** – product catalog and pricing
- **Orders** – order records and timestamps
- **Order Items** – products associated with each order
- **Payments** – payment details and transaction status

---

## 🔗 Relationships
- One-to-many relationship between **Customers → Orders**
- One-to-many relationship between **Orders → Order Items**
- One-to-many relationship between **Products → Order Items**
- One-to-one or one-to-many relationship between **Orders → Payments**

Entity relationships are enforced using **primary keys** and **foreign keys** to maintain referential integrity.

---
