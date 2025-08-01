📚 Smart Library System
Welcome to the Smart Library System, a Java-based console application designed to manage a library's book collection efficiently. This project allows users to add books, borrow books, and access a study section, all through an interactive command-line interface. Built with Object-Oriented Programming (OOP) principles, this system is perfect for learning and demonstrating core Java concepts.

✨ Features

Add Books: Users can add new books to the library archive by providing the book title, ISBN, and author name.
Borrow Books: Users can borrow books, view the issue date, and get a return deadline (15 days) with a penalty warning for late returns.
Study Section: A simple feature for users to access a study area within the library.
Book Catalog Display: Displays a pre-populated list of books with details like title, author, and ISBN.
User-Friendly Interface: Clean console output with formatted book details and personalized greetings.


🚀 Getting Started
Prerequisites

Java Development Kit (JDK): Ensure JDK 8 or higher is installed.
IDE or Terminal: Use an IDE like IntelliJ IDEA, Eclipse, or run via the command line.

Installation

Clone the Repository:
git clone https://github.com/your-username/smart-library-system.git


Navigate to the Project Directory:
cd smart-library-system


Compile the Code:
javac *.java


Run the Application:
java Library_main




📖 Usage

Start the Program:

Run Library_main.java to launch the Smart Library System.
Enter your name when prompted.


Choose a Section:

Select from three options:
1) Add Book: Add a new book to the library archive.
2) Borrow Book: Borrow a book and view borrowing details.
3) Study Here Book: Access the study section.


Enter a number (1, 2, or 3) to proceed.


Follow Prompts:

For adding or borrowing books, provide details like book title, ISBN, and author name.
The system will display confirmation messages and relevant information (e.g., return date for borrowed books).




🛠️ Project Structure
The project consists of the following Java classes:

Library_main.java: The main class that serves as the entry point, handles user input, and directs to other sections.
Add_book.java: Extends Collection_Book to manage the addition of new books to the library archive.
Borrow_bookA.java: A POJO (Plain Old Java Object) class with getters and setters for book attributes (title, author, ISBN).
Borrow_bookB.java: Extends Collection_Book to handle the borrowing process, including issue and return date calculations.
Collection_Book.java: Manages the book catalog display and stores new book details.


💡 OOP Concepts Used
This project leverages key Object-Oriented Programming principles to ensure modularity and maintainability:

Encapsulation:
The Borrow_bookA class encapsulates book attributes (title, author, ISBN) with private fields and public getters/setters.


Inheritance:
Add_book and Borrow_bookB extend Collection_Book to reuse the book catalog display functionality.
Library_main extends Add_book to inherit its methods.


Polymorphism:
The meth1 method in Collection_Book is overloaded to handle different parameter sets for displaying books and adding new ones.


Abstraction:
The system abstracts complex library operations into simple user interactions via the console interface.




📝 Example Output
Adding a Book
      **********************************************************
            *    Welcome to the Smart Library System!!    *
            *                                             *

 ** PLJ Enter your name : Alice

 ** Which Section Would you Go
1) Add Book
2) Borrow book
3) Study Here Book
Enter your choice Btw (1,2,3): 1

Welcome To Book Add Section : Alice 

Enter your Book name : Python Programming
Enter Your Book ISBN no : 108
Enter author name : John Doe

Your Book Name is [Python Programming].
Your Book ISBN no is [108].
Your Book Author name is [John Doe].

               ********************************
               *                              *
               * Book => Python Programming   *
               * Author => John Doe           *
               * ISBN => 108                  *
               *                              *
               ********************************

Thank you for Adding The Book To Archive Alice..

Thankyou For Visitiing Library [Alice]

Borrowing a Book
Welcome [Alice] in Borrow Book Section.

               ********************************
               *                              *
               * Book => Core Java.           *
               * Author => Kishan Basina.     *
               * ISBN => 101                  *
               *                              *
               ********************************
[... more books ...]

Enter Book Name : Core Java
Enter Your Book ISBN no : 101
Enter Book author name : Kishan Basina

You Borrowed book [Core Java].
Book ISBN no is [101].
Book Author name is [Kishan Basina].
Book Issue Date: 2025-08-01

 ** After 15 Days PLJ Return The Book
 ** This Is the last date of Return The Book [2025-08-16]
 ** If You not Return in Time So 100 RS Penality for Everyday.!!

Thankyou For Visitiing Library [Alice]


🌟 Future Enhancements

Database Integration: Store books in a database instead of console output.
GUI Interface: Develop a graphical user interface using JavaFX or Swing.
Return Book Feature: Add functionality to return borrowed books and calculate penalties.
User Authentication: Implement login for personalized user experiences.
Search Functionality: Allow users to search books by title, author, or ISBN.


🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m "Add feature").
Push to the branch (git push origin feature-branch).
Open a Pull Request.


📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

📬 Contact
For questions or suggestions, feel free to reach out via GitHub Issues or contact the repository owner.
Happy Coding! 📚✨
