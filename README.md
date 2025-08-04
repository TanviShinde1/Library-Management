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
