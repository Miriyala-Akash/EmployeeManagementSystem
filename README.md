Employee Management System using Python & MySQL

This is a simple Employee Management System built with Python and MySQL. It allows you to manage employee records through a console-based menu, performing operations like adding, removing, promoting, and viewing employees.

✨ Features

Add new employees with ID, Name, Post, and Salary

Remove existing employees by ID

Promote employees by increasing their salary

Display all employee records in a clean format

Interactive menu-based system

🛠️ Technologies Used

Python 3

MySQL Database (mysql-connector-python for connectivity)

⚙️ Setup Instructions

Clone the repository

git clone https://github.com/your-username/employee-management-system.git
cd employee-management-system


Install dependencies

pip install mysql-connector-python


Setup MySQL database

Create a database named emp:

CREATE DATABASE emp;


Create the employees table:

CREATE TABLE employees (
  id INT PRIMARY KEY,
  name VARCHAR(100),
  position VARCHAR(100),
  salary FLOAT
);


Update database credentials
Inside the code, edit the MySQL connection details:

con = mysql.connector.connect(
    host="localhost",
    user="root",
    password="your_password",
    database="emp"
)


Run the program

python employeemanagementsystem.py

📸 Example Usage
Welcome to Employee Management Record
Press:
1 to Add Employee
2 to Remove Employee
3 to Promote Employee
4 to Display Employees
5 to Exit

🚀 Future Improvements

Add a GUI (Tkinter/Flask web interface)

Input validation & error handling improvements

Export employee records to CSV/Excel

👨‍💻 Author

Developed by Miriyala Akash.
Feel free to use, modify, and improve this project! Contributions are welcome.
