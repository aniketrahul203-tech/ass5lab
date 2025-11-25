Capstone-assignment
Project Description
This project is a Capstone-level Student Management Application developed in Java.
It integrates exception handling, inheritance, interfaces, multithreading, file handling, serialization-like CSV parsing, and collections into a single comprehensive system.

The application allows users to manage student records, search and delete by name, update entries, sort student data, and persist all records into a file.
It also demonstrates the use of RandomAccessFile for low-level file reading.

Objectives
To implement advanced exception handling using custom exceptions.
To apply inheritance & abstraction through an abstract Person class.
To implement an interface-driven design (RecordActions).
To use synchronized methods ensuring thread-safe operations.
To perform file handling using FileReader, FileWriter, BufferedReader, BufferedWriter, and RandomAccessFile.
To use multithreading via a Loader animation thread.
To maintain student data using HashMap and List collections.
To demonstrate CSV-based data persistence.
Features
✔ Object-Oriented Design
Person → abstract base class
Student → child class with roll number, email, marks, grade
Implements method overriding via displayInfo()
Method overloading via calculateGrade() (double/int)
✔ Custom Exceptions
InvalidInputException – thrown for invalid or empty fields
StudentNotFoundException – thrown when searching/updating/deleting missing records
✔ File Handling
Persistence using CSV format
Load and Save using:
BufferedReader
BufferedWriter
FileWriter
FileReader
Demonstrates RandomAccessFile to preview first stored record
✔ Multithreading
Loader class creates a threaded loading animation for:
Adding student
Updating student
Saving data
✔ Complete Student Management (CRUD + Sorting)
Add Student
View All Students
Search Student (by name)
Delete Student (by name)
Update Student (by roll number)
Sort Students by Marks (descending)
Save & Exit
✔ Data Structure
Stores all student entries in a HashMap<Integer, Student> for O(1) operations.
Technologies Used
Language: Java
Concepts Implemented:
Abstraction
Inheritance
Interfaces
Collections (HashMap, List)
Multithreading
Exception Handling
File Handling (Character Streams & RandomAccessFile)
CSV Parsing and Serialization
IDE/Editor: VS Code / IntelliJ IDEA / Eclipse
Execution Environment: Java JDK 8 or above
