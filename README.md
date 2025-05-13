# library_schema
# 📚 Library Management System (MySQL)

## 📌 Description
This project implements a complete relational database system for managing a library using MySQL. It includes members, books, authors, borrowing records, and many-to-many relationships between books and authors.

## 🎯 Features
- Track members and their borrowing history
- Maintain book inventory
- Manage author-book relationships (many-to-many)
- Automatically handle data integrity with PK, FK, UNIQUE, and NOT NULL constraints

## 🛠 How to Run / Import

1. Clone the repository or download the `.sql` file.
2. Open your MySQL client (e.g., phpMyAdmin, MySQL Workbench, or terminal).
3. Run the `library_schema.sql` script:
   ```sql
   SOURCE path/to/library_schema.sql;
