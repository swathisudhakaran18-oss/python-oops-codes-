OOP Concepts in Python

A beginner-friendly Jupyter Notebook demonstrating core Object-Oriented Programming (OOP) concepts in Python through simple, practical examples.

📌 Overview

This notebook covers OOP fundamentals using two real-world style examples:

Person → Student / Teacher – demonstrates inheritance and method reuse
Bank Account / Savings Account – demonstrates encapsulation and inheritance with real-world logic (deposits, withdrawals, interest)
🧠 Concepts Covered
Classes & Objects – creating blueprints and instances
Constructors (__init__) – initializing object attributes
Inheritance – child classes (Student, Teacher, SavingsAccount) reusing and extending a parent class (Person, Account)
super() – calling the parent class constructor from a child class
Encapsulation – bundling data (balance, owner) and behavior (deposit, withdraw) inside a class
Method Overriding / Specialization – child classes adding their own unique methods (study(), teach(), add_interest())
📂 File Structure
├── oop_code_works_simp.ipynb   # Main notebook with all examples
└── README.md                   # Project documentation
🚀 Examples in the Notebook
1. Person, Student & Teacher

A base Person class with name and age. Student and Teacher inherit from it and add their own attributes (major, subject) and methods (study(), teach()).

2. BankAccount

A simple class with deposit() and withdraw() methods managing an account balance.

3. Account & SavingsAccount

An Account base class with deposit/withdraw logic, extended by SavingsAccount, which adds an interest_rate and an add_interest() method.

🛠️ Requirements
Python 3.x
Jupyter Notebook / JupyterLab
▶️ How to Run
Clone or download this repository
Open the notebook:
bash
   jupyter notebook oop_code_works_simp.ipynb
Run each cell in order to see the output
📖 Sample Output
Hello, my name is swathi and I am 25 years old.
Hello, my name is ashwin and I am 30 years old.
swathi is studying Computer Science.
Professor ashwin is teaching Mathematics.

Deposited ₹1500. New balance: ₹6500
Withdrew ₹1000. Remaining balance: ₹1000

Deposited 500. New balance: 1500
Interest of 75.0 added. New balance: 1575.0
Withdrew 200. Remaining balance: 1375.0
📄 License

Feel free to use and modify this notebook for learning purposes.
