# 📚 Library Management System – SQL Schema Design

## 📌 Overview
This project is part of my SQL Developer Internship task. I designed a relational database schema for a **Library Management System** using MySQL.

## 🧱 Tables Created
1. **Categories** – Stores book categories
2. **Authors** – Stores author info
3. **Books** – Stores book details
4. **Members** – Stores member details
5. **Loans** – Stores info about book loans

## 🔗 Relationships
- Each book is written by an author and belongs to a category.
- Each member can borrow multiple books.
- A loan connects a member to a book.

## 🔧 Tools Used
- MySQL Workbench
- GitHub
- ER Diagram created using draw.io
## 🧠 Key Concepts Applied
- DDL Commands (`CREATE TABLE`)
- Primary and Foreign Keys
- AUTO_INCREMENT
- Normalization
- ER Diagram

## 🖼️ ER Diagram
Included in this repo as `ER_DIAGRAM.png`

## 🚀 How to Use
1. Import the SQL script (`schema.sql`) into MySQL Workbench.
2. The schema `LibraryDB` and all tables will be created.
