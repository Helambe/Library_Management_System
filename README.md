# Library Management System

## Overview

The Library Management System is a C++ application designed to facilitate the management of library resources, including the renting and purchasing of books. The system provides an efficient way for users to track available books, manage customer information, and handle billing for different types of books.

## Features

- **Book Management**: 
  - Add, edit, and delete book records.
  - Search for books by title, author, or genre.

- **Book Renting**: 
  - Rent books to customers with due dates and tracking.
  - Manage returns and calculate late fees.

- **Book Purchasing**: 
  - Record purchases of new books for the library inventory.
  - Keep track of purchased books and their costs.

- **Billing System**: 
  - Generate bills for rented and purchased books.
  - Support different pricing models for various book types (e.g., new, used, reference).

- **Customer Management**: 
  - Add, edit, and delete customer records.
  - Track rental history for each customer.

## Technologies Used

- C++
- Object-Oriented Programming (OOP) principles
- Standard Template Library (STL)
- File handling for data persistence

## Installation

To set up the Library Management System on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/library-management-system.git

2. Navigate to the project directory:
   cd library-management-system

3. Compile the source files:
   g++ main.cpp -o library_management_system

4. Run the application:
   ./library_management_system
