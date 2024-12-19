# University Management System

This project implements a simple **University Management System** using C++. It allows users to:

1. Add new student information.
2. Search for existing students by their Roll Number.
3. Update the address of a student.

The program uses file handling to store and manage student records persistently.


## Features

### 1. Add Student
- Prompts the user to input details such as Roll Number, Name, Subject, and Address.
- Stores the data in a file (`university.txt`) for future use.

### 2. Search Student
- Allows the user to search for a student by their Roll Number.
- Displays the student's details if found.

### 3. Update Student Data
- Enables the user to update the address of a student.
- Searches for the student by Roll Number and modifies their address in the file.

### 4. Exit
- Safely exits the application.


## Project Structure

### Files
- **main.cpp**: Contains the source code for the application.
- **university.txt**: Stores the student records in the format:
