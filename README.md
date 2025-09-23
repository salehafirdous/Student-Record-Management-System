# Task 2: Student Record Management System

This project is part of my **Elevate Labs Java Developer Internship**.  
The objective is to create a **CLI (Command-Line Interface) based CRUD system** for managing student records using **Java**.

In this task, I:
- Designed a `Student` class with fields: ID, Name, and Marks.
- Applied **encapsulation** using private fields with getters and setters.
- Used **ArrayList** to store and manage multiple student records dynamically.
- Implemented **CRUD operations**:
  - Add Student
  - View Students
  - Update Student (by ID)
  - Delete Student (by ID)
 -Built a **menu-driven interface** using loops and `Scanner` for continuous interaction.
- Displayed student details neatly using the `toString()` method.

## Features
- Add new student records (ID, Name, Marks)
- View all student records
- Update an existing student record (by ID)
- Delete a student record (by ID)
- Loop-based menu (runs until user exits)
- Uses `ArrayList` for dynamic storage
  
## Class Structure
```
com.elevatelabs.tasks.task2
├── Student.java # Model class with given fields.
└── StudentManagementSystem.java # Main class with CRUD operations.
```
## Example Output
Student Management System 
1. Add Student
2. View Students
3. Update Student
4. Delete Student
5. Exit
Enter your choice: 1
Enter Student ID: 101
Enter Student Name: Saleha Syed
Enter Student Marks: 89.5
✅ Student added successfully


Name: Saleha Firdous Syed Qamar  
Domain: Java Full Stack Development


