# 🏦 Banking System Simulator (Core Java Mini Project)

## 📘 Overview
The **Banking System Simulator** is a console-based Java application that replicates core banking operations such as account creation, deposits, withdrawals, transfers, and balance inquiries.  
It demonstrates clean **Object-Oriented Programming (OOP)** design with strong emphasis on **exception handling**, **collections**, and **multithreading**.

---

## ⚙️ Key Features
- 🔹 Create new accounts with unique auto-generated account numbers  
- 🔹 Deposit and withdraw funds with input validation  
- 🔹 Transfer money securely between accounts  
- 🔹 View account balance and details  
- 🔹 Handle invalid inputs gracefully using **custom exceptions**  
- 🔹 Perform concurrent transactions using **synchronized threads**  

---

## 🧩 Technologies & Concepts
- **Core Java**, **OOP Principles (Encapsulation, Inheritance, Polymorphism)**  
- **Collections Framework** – ArrayList, HashMap  
- **Streams & Lambda Expressions** for searching/filtering accounts  
- **Custom Exceptions** for validation and error handling  
- **Multithreading & Synchronization** to ensure thread safety  

---

## 🏗️ Project Structure
📦 BankingSystemSimulator
┣ 📂 banking
┃ ┣ Account.java
┃ ┣ Bank.java
┃ ┣ BankingSystemSimulator.java ← main class
┃ ┗ TransactionTask.java
┗ 📂 exceptions
┣ InvalidNameException.java
┣ InvalidAmountException.java
┣ InsufficientBalanceException.java
┗ AccountNotFoundException.java

---

## 🖥️ How to Run
1. Open the project in **Eclipse IDE** (or any Java IDE).  
2. Ensure **JDK 8 or above** is installed.  
3. Right-click `BankingSystemSimulator.java` → **Run As → Java Application**.  
4. Use the console menu to perform operations like create, deposit, withdraw, transfer, etc.

## 📊 Sample Output
1. Create Account
2. Access Existing Account
3. Exit
Enter your choice: 1
Enter account holder name: Chaitanya
✅ Account created successfully!
Account Number: CH1234

---


---

## 👨‍💻 Developed By
**Chaitanya Vijay Chaudhari**  
🎓 B.E. (Information Technology), Pravara Rural Engineering College  
📅 Batch: 2021–2025  

---

⭐ *A demonstration of clean OOP design, exception safety, and Java concurrency.*

