Project Overview This repository contains a complete MySQL database solution for a bookstore management system. The database tracks books, authors, publishers, customers, orders, and inventory with appropriate relationships and access controls.

Features 
Designed the complete database schema and created all tables.
Role-based access control and created the repository.
ER diagrams and database visuals.
Database Schema The bookstore_db contains 13 related tables:

Core Tables

Books: book, book_language, book_author
Publishing: publisher, author
Customers: customer, customer_address
Orders: cust_order, order_line, order_history
Supporting: address, country, address_status, shipping_method
Key Features

Proper normalisation (3NF)
Comprehensive foreign key relationships
Auto-incrementing primary keys
Appropriate constraints (NOT NULL, UNIQUE)
