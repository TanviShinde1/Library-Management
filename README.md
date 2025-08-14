# Library-Management
Library database schema using Oracle SQL with normalized tables and relationships ..


#ORACLE SQL

#Entities and Tables
1. Authors – Stores author details.
2. Books – Stores book information, linked to categories.
3. Categories – Types of books.
4. BookAuthor – Many-to-many relationship between books and authors.
5. Members – Library members who can borrow books.
6. Staff – Staff members who looks after loans.
7. Loans – Tracks book details.


#Relationships
1. A book can have multiple authors
2. A book belong to genre
3. A member can borrow books
4. A member can issue loans
5. Author can have multiple books

#SQL FEATURES USED
1.Constraints 
2.Datatypes

#TASKS GIVEN:
Task 1 – Database Schema Design
Created tables for books, authors, categories, members, loans, and staff. Added primary keys, foreign keys, and relationships between them.

Task 2 – Data Insertion & Handling Nulls
Added sample data to all tables, handled missing values with NULL, updated incomplete data, and deleted unnecessary records.

Task 3 – SELECT Queries
Wrote queries to find and display specific data using filters, sorting, and conditions like WHERE, LIKE, and BETWEEN.

Task 4 – Aggregate Functions & Grouping
Used COUNT, SUM, AVG, GROUP BY, and HAVING to summarize data like books per category or average loan time.

Task 5 – SQL Joins
Combined data from multiple tables using INNER, LEFT, RIGHT, and FULL OUTER JOIN, plus multi-table joins for detailed results.

Task 6 – Subqueries & Nested Queries
Wrote queries inside other queries to filter, calculate, and get related data using IN, EXISTS, and correlated subqueries.

Task 7 – Creating Views
Designed views to simplify complex queries and make data easier to read. Simulated views with SELECT statements due to limited database privileges.
And also written only queries for understanding.
