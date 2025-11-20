# Python-ASSIGNMENT-2
Library Book Manager (CLI)

Student Details

NAME: ADITYA

ROLL NO: 2501060126

PROGRAM: BCA (AI & DS)

SECTION: A

Project Overview

This is a Command Line Interface (CLI) based Library Management System built using Python. It addresses the real-world problem of managing university library records by digitizing the tracking of books and student borrowing history.

The system allows librarians to manage book inventory, search for books, and handle the borrowing and returning process efficiently.

Features

Book Management: Add new books with ID, Title, Author, and Quantity.

View Inventory: Display all available books in a formatted table.

Search System: Search for books by ID or Title (supports partial matching).

Borrowing System: Tracks student names and updates stock automatically.

Return System: Returns books to inventory and clears student records.

Data Persistence (Bonus): Automatically saves and loads data using books.csv and borrowed.csv, so data isn't lost when the program closes.

Project Structure

library_manager/
│
├── library.py          # Main application script
├── books.csv           # Stores book inventory data (Auto-generated)
├── borrowed.csv        # Stores borrowing records (Auto-generated)
└── README.md           # Project documentation


Prerequisites

Python 3.x installed on your system.

How to Run

Open your terminal or command prompt.

Navigate to the project folder.

Run the script:

python library.py


Follow the on-screen menu options to navigate the system.

Key Concepts Used

Data Structures: Dictionaries (nested), Lists.

Control Flow: if-elif-else logic, while loops for the menu.

File Handling: csv module for reading/writing data.

Exception Handling: try-except blocks for robust input validation.

List Comprehensions: Used for generating reports of borrowed books.
