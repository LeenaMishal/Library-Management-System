Library Management System

This application is a desktop Library Management System developed using Java Swing and MySQL. The system is designed to help manage library operations such as searching for books, borrowing and returning copies, and managing reservations.

The system supports two types of users: Librarians and Members. Each user has different permissions and features inside the application.

Application Workflow

User Authentication
Users can log in using their email and password. New users can create an account using the sign-up page. After login, the system redirects the user to the appropriate dashboard depending on their role.

Book Search
Users can search for books using different attributes such as title, author, ISBN, or category. The system displays the available copies and their current status.

Borrowing Books
If a copy of the selected book is available, the user can borrow it. The system records the loan with the loan date and due date.

Returning Books
Users can return borrowed books. Once returned, the system updates the copy status to available and records the return date.

Loan Renewal
Users can renew a borrowed book if there are no active holds on that book and the loan is not overdue.

Hold (Reservation) System
If all copies of a book are currently borrowed, users can place a hold request. The system places the user in a queue and notifies them when a copy becomes available.

Librarian Management Features
The librarian dashboard allows administrators to manage the system by adding new books, editing book details, deleting books, managing copies, and viewing all members and loans.

Technologies Used

* Java
* Java Swing
* MySQL
* JDBC
* Maven

Project Structure

src/main/java/com/mycompany/library

dao → Database operations
db → Database connection
model → Data models
ui → User interface
util → Utility classes

Team Members

* Leena Almutairi – Database design and schema creation
* Sana Al-Edilbi – Program implementation and core coding
* Safia Jalal – Assisting in coding and debugging
* Zainab Komailah – Data insertion and testing
* Raghad Alobaid – Report writing and documentation
