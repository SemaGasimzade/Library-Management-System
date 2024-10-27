# Library Management System

## Project Overview
This project implements a comprehensive Library Management System designed to efficiently organize and manage library resources. 

## Data Sources
In this project, I created and populated several tables to serve as the foundation for the Library Management System. Each table was designed to hold specific data relevant to the library’s operations. The following tables were created:

#### Books Table: This table stores information about each book in the library, including fields such as:



book_id: Unique identifier for each book

book_name: Title of the book

book_author: Author(s) of the book

book_genre: Genre of the book

availability: Current availability status (available, checked out, etc.)



#### Readers Table: This table contains details about library patrons, with fields including:




reader_id: Unique identifier for each reader

first_name: Reader's first name

last_name: Reader's last name

email: Reader's email address

phone_number: Reader's phone number



#### Orders Table: This table tracks all book loan and return transactions, including:




order_id: Unique identifier for each order

reader_id: Reference to the reader borrowing or returning the book

book_id: Reference to the book being borrowed or returned

order_date: Date the book was borrowed

return_date: Date the book was returned

## Data Insertion
To populate these tables with sample data, I wrote SQL scripts that insert multiple entries, simulating real-world scenarios. This allows for comprehensive testing of the library management processes and ensures the system functions as intended.

## Tools
-ORACLE SQL-Database Management

## Packages and Procedures
In this project, I developed several packages and procedures to enhance the functionality of the Library Management System.

#### Book Management
I implemented procedures for issuing books to readers and processing returns. These procedures ensure that the system accurately tracks book availability and updates transaction records accordingly.

#### Availability Check
A dedicated procedure was created to check the availability status of books, allowing both library staff and readers to easily ascertain if a book can be borrowed.

#### Reader Management
I also designed packages to handle reader registration and updates. This includes procedures for adding new readers to the system and updating existing reader information, ensuring that the library maintains accurate and up-to-date records.

These packages and procedures streamline operations, improve user experience, and maintain data integrity within the system.
