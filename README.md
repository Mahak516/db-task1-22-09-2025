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
