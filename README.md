Riwi School - Student Management System
A simple, interactive Command Line Interface (CLI) application built with Python to manage student records. This project demonstrates basic CRUD (Create, Read, Update, Delete) operations using dictionaries and lists.
🚀 Features

    Register Students: Create new student profiles with an auto-incrementing ID.
    Consult All: View a complete list of all registered students and their status.
    Search System: Find students easily by searching for their ID or Name (case-insensitive).
    Update Records: Modify specific fields (Name, Age, Course, or Status) without overwriting the entire record.
    Delete Records: Remove students from the system permanently.
    Activity Log: Maintains a background record of all registrations, updates, and deletions.

🛠️ Technical Details

    Language: Python 3.x
    Data Structures:
        students: A dictionary for O(1) complexity lookups by ID.
        record: A list to store the history of actions.
    Key Concepts: Global variables, list comprehensions, dictionary manipulation, and modular function design.

📋 How to Use

    Clone the repository or copy the code to a file named main.py.
    Run the script using your terminal:
    bash

    python main.py

    Usa el código con precaución.
    Follow the menu instructions:
        Enter 1 to add a student.
        Enter 2 to see the full list.
        Enter 3 to search (works with partial names).
        Enter 4 to update (press Enter to skip fields you don't want to change).
        Enter 5 to delete a record.
        Enter 0 to exit.

📝 Example Record Format
Each student is stored with the following attributes:
python

{
    "id": 0,
    "name": "John Doe",
    "age": 22,
    "course": "Software Development",
    "state": True  # True = Active / False = Inactive
}

Usa el código con precaución.
Developed as a practice project for Python fundamentals.
Would you like me to add a "Future Improvements" section to the README, such as saving the data to a CSV or JSON file?
