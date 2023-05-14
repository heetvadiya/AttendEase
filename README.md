# Attendance Management System

Attendance Management System is a web-based application designed to automate and simplify the process of recording and tracking attendance of students in schools or colleges. The system provides a user-friendly interface for teachers, students, and administrators to manage attendance records, generate reports, and track attendance trends.

## Features

- Secure login for administrators, teachers, and students
- Multiple user roles with different levels of access
- Easy attendance recording with automatic calculation of attendance percentages
- Automated notification to parents for absentee students
- Comprehensive attendance reports with graphs and charts
- Export attendance data to CSV or PDF files

## Technologies Used

- HTML/CSS
- PHP
- MySQL
- Bootstrap
- JavaScript

## Installation

1. Clone the repository or download the source code as a zip file.
2. Create a new database in MySQL/MariaDB and import the SQL file (`attmgsystem.sql`) provided in the `database` folder.
3. Update the database configuration in `connect.php` file.
4. Place the entire project folder in the web server's document root directory.
5. Launch the web application in your web browser by typing `http://localhost/attmgsystem` in the address bar.

## Usage

- Login to the application using your credentials.
- Depending on the user role, different functionalities will be available.
- Teachers can record attendance for their classes and generate reports for their students.
- Students can view their attendance records and parents will be notified if their child is absent.
- Administrators can manage users, view attendance reports, and export data.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
