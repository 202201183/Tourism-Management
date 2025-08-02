# 🧳 Tourism Management System

A **Database Management System (DBMS)** project developed as part of the course **IT214 - Database Management Systems**. The project models and manages tourism-related data including destinations, bookings, accommodations, transportation, activities, payments, and more.

## 📁 Project Overview

This project aims to develop an efficient and normalized relational database system to manage tourism-related operations. It provides:

- Interfaces for both logged-in and non-logged-in users.
- Booking and payment management.
- Admin-level functionalities to manage destinations, services, and customers.
- Structured data handling for tourism activities, accommodations, and events.

---

## 📌 Key Features

- **User Roles**: Distinction between logged-in users, non-logged-in users, and admins.
- **Booking System**: Stores detailed data of bookings, check-ins, and services opted.
- **Accommodation & Transport**: Manages availability, pricing, and documentation.
- **Review & Ratings**: Tracks user feedback for quality assessment.
- **Event Listings**: Records local events and fests for travel planning.
- **Financial Management**: Tracks transactions, payments, and refunds.
- **BCNF Normalization**: All tables are normalized to eliminate redundancy.

---

## 📂 Database Schema

Key tables include:

- `Customer`, `Admin`, `Destination`
- `Accommodation`, `Transportation`, `Activities`
- `Booking`, `Payment`, `Review`, `Refund`
- `EventsAndFests`, `Popular_Attractions`, etc.

All tables are constructed using appropriate **Primary Keys**, **Foreign Keys**, and `ON DELETE CASCADE` constraints.

---

## 🧠 Sample SQL Queries

- Retrieve top-rated summer bookings.
- Find destinations popular among 18–30 age group.
- Track admin-specific booking income.
- View available transport and activities in a specific location.
- Analyze booking statistics beyond average rates.

---

## 🧮 Normalization Proofs

Each relation has been carefully examined for **functional dependencies** and normalized up to **Boyce-Codd Normal Form (BCNF)**. This ensures:

- Data consistency
- Reduced redundancy
- Optimal query performance

---

## 🛠 Technologies Used

- **SQL (DDL & DML)**
- **MySQL / PostgreSQL**
- **Dia**

---

## 🚀 How to Run

1. Clone this repository.
2. Run the DDL scripts to create the database schema.
3. Insert sample data (if available).
4. Use the queries provided to explore functionalities and test conditions.

---

## 📚 Learning Outcomes

- Practical understanding of ER modeling and relational design.
- Proficiency in SQL query writing and optimization.
- Application of database normalization concepts in real-world scenarios.
- Improved database project structuring and documentation skills.

---
