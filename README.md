# Library Book Reservation System

A modern web-based library management system that allows users to search, view, and reserve books. Built with Java Servlets, JSP, and MySQL.

![Library Management System](https://img.shields.io/badge/Java-Servlet-orange)
![Library Management System](https://img.shields.io/badge/JSP-2.3-blue)
![Library Management System](https://img.shields.io/badge/MySQL-8.0-green)
![Library Management System](https://img.shields.io/badge/TailwindCSS-3.0-38B2AC)

## Features

- **User Authentication**
  - Login and logout functionality
  - Role-based access control (Admin and Student)

- **Book Management**
  - View all available books
  - Search books by title
  - Add new books (Admin only)
  - View book details and availability status

- **Reservation System**
  - Reserve available books
  - View reservation history
  - Manage reservations (Admin only)

- **Modern UI**
  - Responsive design using Tailwind CSS
  - Intuitive user interface
  - Beautiful gradients and animations

## Technology Stack

- **Backend**
  - Java Servlets
  - JSP (JavaServer Pages)
  - JDBC for database connectivity

- **Frontend**
  - HTML5
  - Tailwind CSS
  - Font Awesome icons

- **Database**
  - MySQL

## Project Structure

```
LibraryBookReservationSystem/
├── src/
│   └── java/
│       ├── controller/         # Servlet controllers
│       │   ├── BookServlet.java
│       │   ├── LoginServlet.java
│       │   ├── LogoutServlet.java
│       │   └── ReservationServlet.java
│       ├── dao/                # Data Access Objects
│       │   ├── BookDAO.java
│       │   ├── ReservationDAO.java
│       │   └── UserDAO.java
│       └── model/              # Data models
│           ├── Book.java
│           ├── Reservation.java
│           └── User.java
├── web/                        # Web resources
│   ├── WEB-INF/
│   ├── addBook.jsp
│   ├── bookList.jsp
│   ├── dashboard.jsp
│   ├── error.jsp
│   ├── login.jsp
│   ├── reserveForm.jsp
│   ├── searchBook.jsp
│   ├── success.jsp
│   └── viewReservation.jsp
└── build.xml                   # Ant build file
```

## Installation and Setup

1. **Prerequisites**
   - Java JDK 8 or higher
   - Apache Tomcat 9.0 or higher
   - MySQL 8.0 or higher
   - NetBeans IDE (recommended)

2. **Database Setup**
   - Create a MySQL database named `librarydb`
   - Import the provided SQL schema (if available)

3. **Application Setup**
   - Clone the repository
   - Open the project in NetBeans
   - Update database connection details in the DAO classes if needed
   - Build and deploy the application to Tomcat

## Usage

1. **Login**
   - Access the application through your web browser
   - Login with your credentials (Admin or Student)

2. **Admin Features**
   - Add new books to the library
   - View and manage all reservations
   - View all books in the system

3. **Student Features**
   - Search for books
   - View book details
   - Reserve available books
   - View your reservation history

## Screenshots
![Admin Dashboard](https://github.com/user-attachments/assets/88cf5c2d-12c9-4bbd-abc5-72aaed75975c)
*Admin dashboard displaying inventory and reservation status.*

![Student Interface](https://github.com/user-attachments/assets/3908503e-f395-4212-9d3d-36f4f06f7bb3)
*Student interface for browsing and reserving books.*

![Book Listing](https://github.com/user-attachments/assets/c6e1b3aa-06b5-4dae-a7f5-fac1473a5c87)
*Comprehensive book listing with availability indicators.*

![Search Functionality](https://github.com/user-attachments/assets/7fc98d43-ee6f-4713-9201-5a70dcd94767)
*Instant search feature for finding books by title.*

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

**IsuruZenith**

## Acknowledgments

- Tailwind CSS for the beautiful UI components
- Font Awesome for the icons
- MySQL for the database 
