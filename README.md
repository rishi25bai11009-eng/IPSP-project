📚 Student Management System (SMS)

📌 Project Overview

This project implements a simple, robust Command Line Interface (CLI) application for managing student records. It utilizes Python's built-in csv module for data persistence, offering a straightforward and efficient way to handle common data operations (CRUD).

Problem Statement

The goal is to provide a simple automated system to replace manual handling of student records, which often leads to errors, data duplication, and general inefficiency.

✨ Features and Functional Requirements

The system supports the full set of essential database operations (CRUD) through an interactive command-line menu:

No.

Feature

Description

1

Add Student

Allows the user to input data (e.g., ID, Name, Course) for a new student and save it to the CSV file.

2

View Students

Displays a complete, formatted list of all student records currently stored in the system.

3

Search Student

Finds and displays a specific student record based on a search criterion (e.g., Student ID or Name).

4

Update Student

Enables modification of existing data for a selected student record.

5

Delete Student

Permanently removes a specified student record from the system.

⚙️ Technology Stack and Architecture

Component

Detail

Rationale

Language

Python

Chosen for its simplicity, readability, and rich set of libraries.

Data Storage

CSV File

CSV was selected for its simplicity and beginner-friendly implementation, making the data easily viewable outside the application.

Interface

Command Line Interface (CLI)

The primary method of interaction, providing a fast and efficient way to manage data.

🚀 Getting Started

To get a local copy of this project up and running, follow the steps below.

Prerequisites

You need to have Python 3.x installed on your operating system.

Installation and Execution

Clone the repository:

git clone [https://github.com/your-username/student-management-system.git](https://github.com/your-username/student-management-system.git)
cd student-management-system


Run the application:

python main.py


(Assuming your main executable file is named main.py).

The system will start, and you will be presented with the main menu to perform operations.

🧪 Testing Approach

Testing was performed manually using multiple input scenarios to ensure the following:

CRUD Integrity: Verify that adding, viewing, searching, updating, and deleting records function correctly and consistently across different data sets.

Data Validation: Ensure the system handles incorrect or missing user inputs gracefully (e.g., searching for a non-existent ID).

File Consistency: Confirm that the underlying CSV file is correctly updated and records are not corrupted after file rewriting operations.

📈 Non-Functional Requirements

The design prioritizes the following qualities:

Usability: Simple, intuitive CLI menu for easy navigation.

Performance: Fast read/write operations due to the lightweight nature of CSV file handling.

Reliability: Implements basic data validation and robust file handling to ensure data consistency.

Maintainability: Modular functions are used for each functional requirement, making the codebase easy to understand and maintain.

💡 Future Enhancements

The following enhancements are planned or suggested for future development:

Graphical User Interface (GUI): Implement a user-friendly interface using libraries like Tkinter, PyQt, or web frameworks.

Database Integration: Migrate from CSV to a proper relational database (e.g., SQLite, PostgreSQL) or NoSQL database for better data integrity and scalability.

Authentication: Add Login/Logout functionality for user security and access control.

Cloud Deployment: Host the system on a cloud platform (e.g., AWS, GCP) for accessibility.

👤 Author

Name: Rishi Sharma

Department: BTech CSE AIML

Registration No.: 25BAI11009

Note: This project was implemented using Python and the CSV module with modular functions.
