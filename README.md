📚 Online Bookstore SQL Project

📖 Project Overview

This project demonstrates the design and implementation of a relational database for an Online Bookstore. It covers database creation, table design, data import, and a variety of SQL queries ranging from basic retrieval to advanced analytical operations.

The goal of this project is to showcase practical SQL skills in database management, querying, and analysis.

🛠️ Tech Stack
Database: PostgreSQL

Language: SQL

Data Import: CSV files using COPY command

📂 Database Schema
The project consists of three main tables:

Books: Stores book details (title, author, genre, year, price, stock).

Customers: Stores customer information (name, email, phone, city, country).

Orders: Stores order details (customer, book, date, quantity, total amount).

Relationships:

Orders references both Books and Customers.

🔍 SQL Queries Solved

✅ Basic Queries
1.Retrieve all books in the Fiction genre.
2.Find books published after 1950.
3.List all customers from Canada.
4.Show orders placed in November 2023.
5.Calculate the total stock of books available.
6.Find details of the most expensive book.
7.Show customers who ordered more than 1 quantity of a book.
8.Retrieve all orders where the total amount exceeds $20.
9.List all genres available in the Books table.
10.Find the book with the lowest stock.
11.Calculate the total revenue generated from all orders.

🚀 Advanced Queries
12.Retrieve the total number of books sold per genre.
12.Find the average price of books in the Fantasy genre.
13.List customers who placed at least 2 orders.
14.Find the most frequently ordered book.
15.Show the top 3 most expensive Fantasy books.
16.Retrieve the total quantity of books sold by each author.
17.List cities where customers who spent over $30 are located.
18.Find the customer who spent the most on orders.
19.Calculate the remaining stock after fulfilling all orders.

📊 Key Learnings
Designing normalized relational schemas.

# Using joins, aggregations, grouping, and filtering effectively.
# Performing business insights analysis (revenue, customer behavior, inventory tracking).
# Handling data import/export with CSV files.

🚀 How to Run
Clone the repository.

Create the database in PostgreSQL:

sql
CREATE DATABASE OnlineBookstore;
Run the SQL script to create tables and import data.

Execute queries to explore results.

📌 Project Use Cases
This project simulates a real-world bookstore management system, useful for:

Tracking inventory and sales.
Analyzing customer behavior.
Generating business insights for decision-making.
