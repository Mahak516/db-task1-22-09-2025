# db-task1-22-09-2025
sql create tables, databases
1. I create database of ecommerce
2. then use ecommerce as selected database
3. then I create table customers with columns (customer id , name,email,phone,address)
4.  then I create table categories with columns(category id, category name)
5.   then I create table products with columns(product id, name, price, stock,category id as foreign key)
6.    then I create table order with columns(order id, customer id, order date, total, customer id as foreign key)
7. then I create table order items(M:N relationship) with columns(order id, product id, quantity)
8. and last I create table payments with columns(payment id, order id, amount, payment date, payment method, order id as foreign key)


Interview questions:-
**1.What is normalization?**
Ans. Process of organizing data to reduce redundancy and improve data integrity.
(e.g., breaking data into multiple related tables).

**2.Primary key vs Foreign key?**

Ans:Primary Key: Uniquely identifies a record in a table.

Foreign Key: References the primary key of another table, establishing relationships.

**3.What are constraints?**
➝ Rules applied to columns to enforce data integrity (e.g., NOT NULL, UNIQUE, PRIMARY KEY, FOREIGN KEY, CHECK).

**4.What is a surrogate key?**
➝ An artificial unique identifier (like an AUTO_INCREMENT id) instead of natural data (like email).

**5.How do you avoid data redundancy?**
➝ By normalization, using foreign keys, and separating data into related tables.

**6.What is ER diagram?**
➝ A visual representation of entities, attributes, and relationships in a database.

**7.Types of relationships in DBMS?**

One-to-One (1:1)

One-to-Many (1:N)

Many-to-Many (M:N)

**8.Purpose of AUTO_INCREMENT?**
➝ Automatically generates unique IDs for new records.

**9.Default storage engine in MySQL?**
➝ InnoDB (supports ACID transactions and foreign keys).

**10.What is a composite key?**
➝ A primary key made up of two or more columns (e.g., OrderID + ProductID in Order_Items).
