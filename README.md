# Student Database Management System

This C program allows for the management of student data, including adding students, displaying student records, and tracking their courses and grades.

## Features:
- Add a student to the database.
- Display all students' information, including their courses and grades.
- Student ID, name, course details, and grades are stored in a database.

## Requirements:
- **C Compiler** (e.g., GCC)
- **Header files** for I/O operations (standard libraries)

## Setup:

### Step 1: Clone the repository
Clone the repository to your local machine:
git clone https://github.com/Ehidiamen2003/student_database_project.git

### Step 2: Navigate to the project directory
Change to the project directory:
cd student_database_project

### Step 3: Compile the C files
Use a C compiler (e.g., GCC) to compile the program:
gcc main.c studentDatabase_lib.c -o student_database

### Step 4: Run the program
After compiling the code, run the executable:
./student_database

## Program Menu:
Once you run the program, the following menu will appear:

Welcome to Student Database Management System
-----------------------------------------------------
1. Add Student
2. Display All Students
3. Exit
Input your choice:

### Step 5: Add a Student
1. When you select **1. Add Student**, the program will prompt you to enter the student's name, ID, courses, and grades.
   
2. After entering the student's information, the student is added to the database.

### Step 6: Display All Students
1. Select **2. Display All Students** to view a list of all students, including their enrolled courses and grades.

2. The program will display each student's name, ID, and the courses they are enrolled in, along with the grades for each course.

### Step 7: Exit the Program
1. Select **3. Exit** to exit the program.

## Project Structure:
student_database_project/
├── main.c                # Main driver file

├── studentDatabase_lib.c # Functions for adding and displaying student records

├── studentDatabase_lib.h # Header file with function prototypes and structures

└── README.md             # This README file

## License:
This project is licensed under the **MIT License**. See the LICENSE file for more details.
