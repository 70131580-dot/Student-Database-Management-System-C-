# Student-Database-Management-System-C-
Student Database Management System for C++
Student Database System (OOP Project)
Problem Statement
Managing student records manually is prone to errors and data loss. This console-based system allows administrators to input student data, validate it, and store it permanently in a file for reporting and performance tracking.

**OOP Concepts Used
Classes & Objects:** Used for Student and SystemManager.

**Encapsulation:** Private attributes in Student class accessed via public methods.

**Inheritance:** Student inherits from the abstract base class Person.

**Polymorphism**: Used a virtual function displayRole() to handle different user types dynamically.

**Exception Handling**: A try-catch block validates user input (e.g., preventing negative IDs).

**File Handling**: Uses fstream to save and retrieve student data from students.txt.

**Program Flow**
User selects an action from the menu (Add/View/Exit).

Add: Input is validated. If valid, an object is created and written to a text file.

View: The program reads the file, reconstructs objects, and displays them using polymorphic pointers.

Exit: Memory is cleared, and the program terminates.

**How to Run**
**Clone the repository**: git clone <your-link>

**Compile the code**: g++ main.cpp -o student_system

**Run the executable**: ./student_system
