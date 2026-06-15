Week 1:
The Student Management System is a console-based application developed in C++ that helps manage student records efficiently. The system uses file handling to store data permanently and provides a menu-driven interface for easy interaction.

## Features

* Add Student Record
* Display All Student Records
* Search Student by Roll Number
* Update Student Information
* Delete Student Record
* Persistent Data Storage using File Handling

## Technologies Used

* C++
* File Handling (`ifstream`, `ofstream`)
* Functions
* Loops and Conditional Statements

## File Structure

* `main.cpp` – Source code
* `students.txt` – Stores student records

## Data Format

Student records are stored in the following format:

101|ABC
102|XYZ


## Menu Options

1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit

## Concepts Implemented

* File Handling
* CRUD Operations (Create, Read, Update, Delete)
* Menu-Driven Programming
* Data Persistence
* Basic Record Management

## Expected Outcome

A simple and efficient application that allows users to manage student records with permanent storage and easy retrieval of information.

week 2: 
# Bank Management System

A simple console-based Bank Management System developed in C++ using file handling. The application simulates basic banking operations such as account creation, deposits, withdrawals, balance inquiries, and record management.

## Features

* Create a new bank account
* Deposit money into an account
* Withdraw money from an account
* Check account balance
* Display all account records
* Persistent data storage using file handling
* Menu-driven user interface

## Technologies Used

* C++
* Object-Oriented Programming Concepts
* File Handling (`ifstream`, `ofstream`)
* Functions and Control Statements

## Project Structure

```text
BankManagementSystem/
│
├── main.cpp
├── bank.txt
└── README.md
```

## Data Storage

Account information is stored in a text file (`bank.txt`) in the following format:

```text
1001|Rakshith|5000
1002|Rahul|3000
1003|Priya|7000
```

Where:

* Account Number
* Customer Name
* Account Balance

Sample Output
Bank Management System

1. Create Account
2. Deposit
3. Withdraw
4. Check Balance
5. Display Accounts
6. Exit

Choice: 1

Enter Account Number: 1001
Enter Customer Name: Rakshith
Enter Initial Balance: 5000

Account Created Successfully!


