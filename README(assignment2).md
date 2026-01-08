Online Banking Application (Java)
Project Overview
This project is a console-based Online Banking System implemented in Java. It demonstrates core Object-Oriented Programming (OOP) concepts such as class structure, encapsulation, object instantiation, and business logic implementation.

Subject Area
Topic 12: Online Banking Application

Classes Implemented:
BankAccount

Customer

Bank

Features and Requirements Met
Class Creation: Three distinct classes representing the domain entities.

OOP Structure: Implementation of Constructors, Attributes, and Methods.

Encapsulation: Usage of private attributes with public Getter and Setter methods.

Main Function Execution: Creating instances and printing results.

Object Comparison: Logic to compare different objects (account balances and customer IDs).

Class Structure
1. Customer
Attributes: customerId, name, email Method: isSameCustomer(Customer other) checks if two customer objects represent the same person based on ID.

2. BankAccount
Attributes: accountNumber, balance, owner Methods: deposit(double amount) and withdraw(double amount).

3. Bank
Attributes: bankName, accounts (List) Method: showAllAccounts() prints a report of all accounts.

How to Run
Compile the Java file: javac OnlineBankingApp.java

Run the Application: java OnlineBankingApp

Project Defense Notes
Encapsulation: I protected the balance attribute by making it private. It cannot be modified directly, only through deposit or withdraw methods.

Relationships: The BankAccount class contains a Customer object, establishing a relationship between entities.

Constructors: Used to initialize objects with required data immediately upon creation.

Author: Azamat Suinalin
