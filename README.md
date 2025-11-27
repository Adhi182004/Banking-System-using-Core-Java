💳 Mini Project – Banking System (Core Java)

This project is a console-based Banking System developed using Core Java, demonstrating key Object-Oriented Programming (OOP) concepts such as encapsulation, inheritance, polymorphism, abstraction, and the use of Java Collections.

It simulates basic banking operations like managing customers, accounts, transactions, and beneficiaries without using any database or external framework.

🚀 Project Features
👤 Customer Management

Add new customers

View customer details by ID

Store customer data using HashMap

🏦 Account Management

Create accounts for customers

One customer can have multiple accounts

Supports account types (Savings / Current)

Maintains account balances

💰 Transaction Management

Deposit money

Withdraw money

Auto-timestamp using LocalDateTime

Prevents withdrawal if balance is insufficient

👥 Beneficiary Management

Add multiple beneficiaries for a customer

Store beneficiary details

📂 Data Storage (Collections)

No database used

Pure Core Java implementation using:

HashMap

ArrayList

🖥 Menu-Driven Console Interface

Simple text-based UI for navigating all operations.

🛠 Technologies Used
Technology	Usage
Java (Core Java)	Main programming language
OOP Concepts	Classes, Objects, Inheritance, Polymorphism
Collections Framework	HashMap, List
LocalDateTime API	Timestamping transactions
Eclipse IDE	Development environment (recommended)
📁 Project Structure
BankingSystem/
│
├── Customer.java
├── Account.java
├── Transaction.java
├── Beneficiary.java
│
├── BankingService.java
├── BankingServiceImpl.java
│
└── BankingSystemApp.java

🎯 Learning Objectives

Understand and apply OOP concepts

Use Java Collections for data management

Create a modular Java application

Build menu-driven console programs

Implement relationships (One-To-Many, Many-To-Many)

Handle user input and simple validations

▶️ How to Run

Clone or download the repository:

git clone https://github.com/<your-username>/<repo-name>.git


Open in Eclipse or any Java IDE

Run the main class:

BankingSystemApp.java


Follow the menu options in the console

📌 Future Enhancements

Add login system

Add file storage or database

Add transaction history export

Add account type interest calculations

Create GUI using JavaFX or Swing
