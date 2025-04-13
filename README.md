# Bookstore Database Design & SQL Implementation

## Overview
This project involves designing and implementing a relational MySQL database for managing a bookstore's operations. The system handles data related to books, authors, customers, orders, shipping, and more. It offers efficient data storage and retrieval capabilities through a well-structured schema.

## Tools and Technologies
- **MySQL** – For database creation and management
- **Draw.io** – For creating the database schema diagram

## Objectives
- Create a fully normalized and relational database schema
- Implement tables with appropriate data types and constraints
- Set up access roles and permissions
- Enable querying for meaningful insights
- Visualize schema structure with an ERD

## Tables Created
1. `country` – Stores country information.
2. `address` – Stores address details linked to a country.
3. `address_status` – Status of an address (current, old, etc.).
4. `customer` – Stores customer details.
5. `customer_address` – Links customers to multiple addresses.
6. `publisher` – Stores publisher information.
7. `book_language` – Lists available languages for books.
8. `book` – Stores book metadata.
9. `author` – Stores author details.
10. `book_author` – Links books to multiple authors.
11. `shipping_method` – Lists available shipping options.
12. `order_status` – Tracks order status (pending, shipped, etc.).
13. `cust_order` – Captures customer orders.
14. `order_line` – Lists the books in each order.
15. `order_history` – Tracks status changes over time.

## Getting Started
1. Clone this repo.
2. Import the `bookstore_db.sql` file into your MySQL server.
3. Use the `USE bookstore_db;` command to select the database.
4. Run queries to insert, update, or retrieve data as needed.

## ERD
The ERD (Entity-Relationship Diagram) visually illustrates the relationships between all tables in the database.

![ERD](./A_diagram_depicts_a_relational_database_schema_for.png)


## Contributors
- Group Leader: Calvin Wanyama.
- Team Members: Nicole Akeyo, Bongani Nyawose.

## License
This project is intended for academic use only.

## Submission
**Deadline:** 13/04/2025 - 11:59 PM EAT  
**Submission Format:** GitHub Repository link
