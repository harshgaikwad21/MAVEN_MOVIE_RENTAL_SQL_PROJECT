# MAVEN_MOVIE_RENTAL_SQL_PROJECT

![Uploading image.png…]()


<h1>📌Project Overview</h1>
This project explores the Maven Movies dataset using SQL to analyze and generate insights from a movie rental database. The dataset simulates a DVD rental store and includes information about customers, films, actors, rentals, payments, and staff. The primary objective of this project is to practice SQL queries and demonstrate how relational databases can be used for data analysis, reporting, and business decision-making.

# Maven Movies SQL Database Project

## 📖 Overview
This project contains the **Maven Movies Database**, a MySQL-based schema designed for practicing SQL queries and database management.  
It is adapted from the **Sakila Sample Database**, widely used for learning relational database concepts.  

The schema models a **DVD rental business**, including entities such as films, actors, customers, staff, stores, rentals, and payments.

## 🗂️Dataset Description
The Maven Movies dataset contains the following key tables:

- Actor – List of all actors.

- Film – Details of movies including title, release year, rating, and rental duration.

- Category – Genre/category of films.

- Customer – Information about customers who rented movies.

- Rental – Rental transactions and their timestamps.

- Payment – Payment records for rentals.

- Store & Staff – Information about stores and employees.

## 🎯Project Objectives
Understand the database schema and relationships.

- Write SQL queries for data extraction, cleaning, and transformation.

- Answer business-related questions such as:

- Which movies are most popular?

- Who are the top customers based on spending?

- Which genres generate the most revenue?

- What is the rental frequency by month/year?

## 🔍SQL Concepts Covered
- Basic Queries – SELECT, WHERE, ORDER BY, LIMIT

- Filtering – LIKE, IN, BETWEEN, DISTINCT

- Aggregations – COUNT, SUM, AVG, MIN, MAX, GROUP BY, HAVING

- Joins – INNER JOIN, LEFT JOIN, RIGHT JOIN

- Subqueries – Nested queries for advanced filtering

- Window Functions – RANK, DENSE_RANK, ROW_NUMBER

- Data Analysis – Customer segmentation, revenue trends, genre analysis

## 🚀Tools & Technologies
- Database: MySQL

- Querying Language: SQL

- MAVENMOVIES Database – Source of movie rental data


## 📌Key Insights
- Action and Family genres are among the most rented categories.

- A small percentage of customers contribute to the majority of revenue.

- Seasonal trends show peak rentals during specific months.

- High-value customers can be targeted for loyalty programs.



## 📋 Schema Highlights
- **Core Tables:**
  - `actor`, `actor_award`, `film`, `film_actor`, `film_category`
  - `customer`, `rental`, `payment`, `inventory`
  - `staff`, `store`, `address`, `city`, `country`
  - `category`, `language`, `advisor`, `investor`

- **Relationships:**
  - Customers rent films through `rental` linked to `inventory`.
  - Films belong to categories and can feature multiple actors.
  - Payments are tracked per rental and customer.
  - Staff and stores manage operations.

---

## 🛠 Installation & Setup
1. Install **MySQL Server** (version 5.6+ recommended).
2. Clone or download this repository.
3. Open MySQL and execute the script:
   ```sql
   SOURCE create_mavenmovies.sql;
