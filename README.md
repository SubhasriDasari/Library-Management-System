# Library-Management-System
The LibraryManagementSystem is a console-based Java application designed to manage the basic operations of a library. It allows the librarian or user to perform tasks such as adding books, adding students, issuing and returning books, and viewing records.
Key Components and Functionality:
Main Class: LibraryManagementSystem

Acts as the entry point of the program.

Manages the menu-driven interface using a while loop and a Scanner for user input.

Menu Options:

markdown

--- 📖 Library Management System ---
1. Add Book
2. Add Student
3. Issue Book
4. Return Book
5. View Records
6. Exit
User Input Handling:

Uses Scanner to read user input.

Uses try-catch block to validate if the choice entered is a number.

Each case in the switch statement handles a different library operation.

Operations:

Add Book: Takes Book ID, Title, and Author, then adds the book to the system.

Add Student: Takes Student ID and Name, then registers the student.

Issue Book: Links a book to a student for borrowing.

Return Book: Marks the book as returned by the student.

View Records: Displays current books, students, and issued books.

Exit: Safely terminates the program.

Supporting Classes (assumed to be created):

Book: Represents a book with fields like ID, title, and author.

Student: Represents a student with fields like ID and name.

Library: Contains methods like addBook(), addStudent(), issueBook(), returnBook(), and viewRecords().

Features:
User-friendly text-based interface.

Input validation to prevent crashes.

Real-time operation on a simple in-memory database using Java objects.

Can be extended to use file or database storage.

 Use Cases:
Academic project for learning Java OOP and console I/O.

Base template for a GUI or web-based library management system.

Useful in small-scale library setups.

