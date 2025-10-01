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


<h1>Queries and Visualizations</h1>

# 1. Customer Information for Marketing Team
Retrieve customer first name, last name, and email ID.

<img width="519" height="375" alt="Screenshot 2025-09-30 150258" src="https://github.com/user-attachments/assets/986502cb-c479-438f-86c9-4402c28904eb" />


2. Count of Movies with Rental Rate of $0.99

<img width="195" height="102" alt="Screenshot 2025-09-30 151802" src="https://github.com/user-attachments/assets/ee03f87d-a2ff-4213-b4c3-5eea3412b1b3" />


3. Rental Rate Distribution and Movie Count

<img width="334" height="119" alt="Screenshot 2025-09-30 152618" src="https://github.com/user-attachments/assets/e09234f6-57d1-4f0b-9572-f455c00816ee" />


4. Most Common Movie Rating

<img width="302" height="201" alt="Screenshot 2025-09-30 153146" src="https://github.com/user-attachments/assets/b302dc2d-0f8d-4eec-b494-7c263186cb17" />


5. Most Prevalent Rating per Store

<img width="266" height="257" alt="Screenshot 2025-09-30 154604" src="https://github.com/user-attachments/assets/c3c8735e-3dff-48b4-818b-490446cc668f" />


6. List of Films by Name, Category, and Language

<img width="444" height="382" alt="Screenshot 2025-09-30 161426" src="https://github.com/user-attachments/assets/01e4e055-27e1-4e3f-add1-84f0de191381" />


7. Movie Rental Frequency

<img width="297" height="362" alt="Screenshot 2025-10-01 000306" src="https://github.com/user-attachments/assets/346784fa-6abf-4805-9194-f937e7460d60" />


8. Top 10 Grossing Films

<img width="322" height="247" alt="Screenshot 2025-10-01 000457" src="https://github.com/user-attachments/assets/c511d90f-c8fa-427e-a0ff-47687355635b" />


9. Highest Spending Customer


10. Store with Most Revenue


11. Monthly Rentals Count


12. Customers Eligible for Rewards


13. Payments from First 100 Customers


14. Payments Over $5 Since Jan 1, 2006


15. Payments Over $5 for Specific Customers


16. Payments Over $5 for Specific Customers


17. Films with 'Behind the Scenes' Special Feature


18. Unique Movie Ratings and Count


19. Titles Count by Rental Duration


20. Ratings, Movie Count, Length, and Rental Duration


21. Film Count by Replacement Cost with Rental Rates


22. Customers with Less Than 15 Rentals


23. Longest Films Sorted by Length and Rental Rate


24. Categorization of Movies by Length


25. Movie Recommendations by Age Group


26. Store Activity


27. Films Inventory List


28. Actor Movie Count


29. Number of Actors per Film


30. List of Customers Favourite Actors


31. List of Staff and Advisors










