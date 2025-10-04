# MAVEN_MOVIE_RENTAL_SQL_PROJECT
<img width="1125" height="750" alt="image" src="https://github.com/user-attachments/assets/2b32356c-fbd4-4919-ba8a-d486202e3d88" />


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

### 1. Customer Information for Marketing Team
Retrieve customer first name, last name, and email ID.

<img width="519" height="375" alt="Screenshot 2025-09-30 150258" src="https://github.com/user-attachments/assets/986502cb-c479-438f-86c9-4402c28904eb" />

### 2. Count of Movies with Rental Rate of $0.99

<img width="195" height="102" alt="Screenshot 2025-09-30 151802" src="https://github.com/user-attachments/assets/ee03f87d-a2ff-4213-b4c3-5eea3412b1b3" />

### 3. Rental Rate Distribution and Movie Count

<img width="334" height="119" alt="Screenshot 2025-09-30 152618" src="https://github.com/user-attachments/assets/e09234f6-57d1-4f0b-9572-f455c00816ee" />

### 4. Most Common Movie Rating

<img width="302" height="201" alt="Screenshot 2025-09-30 153146" src="https://github.com/user-attachments/assets/b302dc2d-0f8d-4eec-b494-7c263186cb17" />

### 5. Most Prevalent Rating per Store

<img width="266" height="257" alt="Screenshot 2025-09-30 154604" src="https://github.com/user-attachments/assets/c3c8735e-3dff-48b4-818b-490446cc668f" />

### 6. List of Films by Name, Category, and Language

<img width="444" height="382" alt="Screenshot 2025-09-30 161426" src="https://github.com/user-attachments/assets/01e4e055-27e1-4e3f-add1-84f0de191381" />

### 7. Movie Rental Frequency

<img width="297" height="362" alt="Screenshot 2025-10-01 000306" src="https://github.com/user-attachments/assets/346784fa-6abf-4805-9194-f937e7460d60" />

### 8. Top 10 Grossing Films

<img width="322" height="247" alt="Screenshot 2025-10-01 000457" src="https://github.com/user-attachments/assets/c511d90f-c8fa-427e-a0ff-47687355635b" />

### 9. Highest Spending Customer

<img width="453" height="259" alt="Screenshot 2025-10-01 001726" src="https://github.com/user-attachments/assets/f3848667-6e7a-4d91-acd5-9b3b490b4383" />

### 10. Store with Most Revenue

<img width="413" height="157" alt="Screenshot 2025-10-01 003754" src="https://github.com/user-attachments/assets/65979dbb-e5bc-4175-9131-a8afd55ba2fe" />

### 11. Monthly Rentals Count

<img width="413" height="157" alt="Screenshot 2025-10-01 003754" src="https://github.com/user-attachments/assets/0dba62a6-22b1-44cb-8007-5211a355d2ab" />

### 12. Reward users who have rented at least 30 times (with details of customers)

<img width="857" height="372" alt="Screenshot 2025-10-01 010723" src="https://github.com/user-attachments/assets/27296bef-985c-4e42-adea-a3d2de359cde" />

### 13. Payments from First 100 Customers

<img width="511" height="388" alt="Screenshot 2025-10-01 011758" src="https://github.com/user-attachments/assets/aa577e37-e1e7-42c7-b8d1-302bad29a297" />

### 14. Payments Over $5 Since Jan 1, 2006

<img width="478" height="154" alt="Screenshot 2025-10-01 012536" src="https://github.com/user-attachments/assets/7433849c-9791-45cf-9a3d-a173347bfaa9" />

### 15. Payments Over $5 for Specific Customers

<img width="462" height="385" alt="Screenshot 2025-10-01 014132" src="https://github.com/user-attachments/assets/e8aeff5c-07a0-4d24-99da-aa3ceef92462" />

### 16. Films with 'Behind the Scenes' Special Feature

<img width="522" height="368" alt="Screenshot 2025-10-01 020308" src="https://github.com/user-attachments/assets/02784329-268c-4951-bc1a-22dbb9802c09" />

### 17. Unique Movie Ratings and Count

<img width="295" height="191" alt="Screenshot 2025-10-01 122940" src="https://github.com/user-attachments/assets/dcee19e7-2e5c-42c1-9683-9e617b56454c" />

### 18. Titles Count by Rental Duration

<img width="373" height="167" alt="Screenshot 2025-10-01 123836" src="https://github.com/user-attachments/assets/f2605b98-45d0-442a-b274-f569dad2f46a" />

### 19. Ratings, Movie Count, Length, and Rental Duration

<img width="939" height="185" alt="Screenshot 2025-10-01 125127" src="https://github.com/user-attachments/assets/c1d8cb2e-a24c-47f8-9d4b-0990beded825" />

### 20. Film Count by Replacement Cost with Rental Rates

<img width="862" height="348" alt="Screenshot 2025-10-01 130346" src="https://github.com/user-attachments/assets/f285a1a2-ac8f-47e3-83bc-da9bd4fa285b" />

### 21. Customers with Less Than 15 Rentals

<img width="384" height="129" alt="Screenshot 2025-10-01 145156" src="https://github.com/user-attachments/assets/3aa375f9-6f3d-47ca-93cb-ebab7e8a44ca" />

### 22. Longest Films Sorted by Length and Rental Rate

<img width="372" height="348" alt="Screenshot 2025-10-01 145904" src="https://github.com/user-attachments/assets/49707350-769e-44e4-8cb6-987230e43bbb" />

### 23. Categorization of Movies by Length

<img width="465" height="351" alt="Screenshot 2025-10-01 150104" src="https://github.com/user-attachments/assets/057abf31-1621-41de-9f89-4f35e7d7b150" />

### 24. Movie Recommendations by Age Group

<img width="520" height="345" alt="Screenshot 2025-10-01 150235" src="https://github.com/user-attachments/assets/084e5e83-da64-4722-b71b-164ebe42e4f3" />

### 25. Store Activity

<img width="533" height="348" alt="Screenshot 2025-10-01 150512" src="https://github.com/user-attachments/assets/bff6f4e1-255b-4a99-8127-b01fd99b103c" />

### 26. Films Inventory List

<img width="727" height="342" alt="Screenshot 2025-10-01 150827" src="https://github.com/user-attachments/assets/7487e9c3-b6e8-4db1-a62e-70d8623a98ad" />

### 27. Actor Movie Count

<img width="481" height="345" alt="Screenshot 2025-10-01 151008" src="https://github.com/user-attachments/assets/2226db0d-c84a-41cf-a2ea-3ae0f4808e54" />

### 28. Number of Actors per Film

<img width="425" height="352" alt="Screenshot 2025-10-01 151122" src="https://github.com/user-attachments/assets/77ce94f1-6e61-489d-b86e-67aba4962a21" />

### 29. List of Customers Favourite Actors

<img width="455" height="346" alt="Screenshot 2025-10-01 151309" src="https://github.com/user-attachments/assets/c87e3dde-a3af-4224-aef1-9ac229a4c998" />

### 30. List of Staff and Advisors

<img width="377" height="181" alt="Screenshot 2025-10-01 151614" src="https://github.com/user-attachments/assets/4bcb2069-bad7-457f-a7ba-4e6126bb681d" />









