University Management System

This project is a simple University Management System implemented in C++ that allows users to manage student records. The system supports adding, searching, and updating student data. All data is stored in a text file for simplicity.

Features

Add Student: Input student details such as Roll Number, Name, Subject, and Address and store them in a file.

Search Student: Search for a student by their Roll Number and display their details.

Update Student Data: Update the address of a student by their Roll Number.

Requirements

To run this project, you need:

A C++ compiler that supports C++11 or later.

Windows operating system (for windows.h dependency).

A text editor or IDE like Visual Studio Code, Dev-C++, or Visual Studio.

File Structure

university_management.cpp: Contains the main program code.

D:/university.txt: Stores the student data in a readable format.

How to Run

Clone the repository or download the code files.

Open the project in your preferred C++ development environment.

Make sure the D:/ directory exists on your system or update the file paths in the code to your preferred location.

Compile and run the program.

Usage

When the program starts, you will see the main menu with the following options:

Add Student

Search Student

Update Data Of Student

Exit

Follow the prompts to perform the desired operation.

To add a student, provide the Roll Number, Name, Subject, and Address.

To search for a student, enter their Roll Number to view their details.

To update a student's address, enter their Roll Number and the new address.

Known Issues

The program currently uses absolute file paths. Update the file paths for portability.

The program assumes the university.txt file exists and has proper permissions.

Error handling can be improved for edge cases.

Future Improvements

Implement a GUI for better user experience.

Add functionality to delete student records.

Enhance error handling and validation for user inputs.

Make the file path dynamic or configurable.
