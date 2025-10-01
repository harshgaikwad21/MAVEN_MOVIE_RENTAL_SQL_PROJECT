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
