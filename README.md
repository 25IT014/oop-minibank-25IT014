# MiniBank – Object-Oriented Programming Project

## Project Overview

MiniBank is a Java-based banking application developed to demonstrate Object-Oriented Programming (OOP) concepts and advanced Java features. It provides a menu-driven banking system with different account types, transaction processing, input validation, transaction logging, and report generation.

## Features

- **Multiple Account Types:** Savings Account, Current Account, and Fixed Deposit Account.
- **OOP Concepts:** Classes, objects, inheritance, abstraction, encapsulation, and polymorphism.
- **Custom Exceptions:** Handles banking errors such as insufficient funds, invalid amounts, and account not found.
- **Validation:** Uses custom annotations and validation logic to check input data.
- **Transaction Processing:** Supports transaction handling using `ExecutorService` and multithreading.
- **Safe Transfers:** Implements safe transfer logic with ordered account locking.
- **File Handling:** Supports account data persistence and transaction logging.
- **Transaction Reports:** Generates transaction reports.
- **Generics:** Uses a generic `Repository<T>` class.
- **Functional Programming:** Uses a custom functional interface for withdrawal rules.
- **Resource Management:** Demonstrates `AutoCloseable` and try-with-resources.
- **Producer-Consumer Concept:** Demonstrates thread coordination using `wait()` and `notify()`.
- **Command-Line Menu:** Provides a menu-driven interface to interact with the banking system.

## Technologies Used

- Java (Java 17 or later recommended)
- Object-Oriented Programming
- Java Collections and Generics
- Exception Handling
- Multithreading and Concurrency
- File Handling
- Annotations and Functional Interfaces

## Project Structure

```text
oop-minibank-25IT014/
├── MiniBank.java
├── README.md
└── .gitignore
```

The project uses a single Java source file, `MiniBank.java`, containing the main class and its nested classes.

## Requirements

- Java Development Kit (JDK) 17 or later
- VS Code or any Java-compatible editor
- A terminal or command prompt

## How to Run

### Step 1: Open the project folder

Open the project folder in VS Code.

### Step 2: Open the terminal

In VS Code, select **Terminal → New Terminal**.

### Step 3: Compile the program

```bash
javac MiniBank.java
```

### Step 4: Run the program

```bash
java MiniBank
```

Follow the menu displayed in the terminal to explore the application.

## Runtime Files

The application may create runtime files and directories for:

- Account data: `data/accounts.dat`
- Transaction logs: `data/logs/transactions.log`
- Generated transaction reports

These files are generated while running the application and are not required to be committed to the source-code repository.

## Learning Objectives

This project demonstrates the practical application of Java OOP concepts, exception handling, generics, annotations, file handling, and multithreading in a banking-system scenario.

## Author

**Name:** Changanai Janki  
**Roll Number:** 25IT014  
**Class:** IT-1
