# Bank System

This project is a **Bank System application** developed in **C++**, demonstrating **Object-Oriented Programming (OOP)**, **File Handling**, and **Vector-based data management**. It simulates a real-world banking environment with distinct **Client**, **Employee**, and **Admin** modules, each offering specialized functionalities.

---

## 🚀 Features

### **Client Module**
- Secure login using ID and password.
- Deposit, withdraw, and check account balance.
- Transfer money to other clients.
- Input validation for **name**, **password**, and minimum balance (1500).

### **Employee Module**
- Secure login using ID and password.
- Add new clients, search for clients, and list all clients.
- Edit client information (name, password, balance).
- Display employee info and manage client data.

### **Admin Module**
- Inherits all Employee functionalities.
- Add new employees, search for employees, and list all employees.
- Edit employee information (name, password, salary).

---

## 🛠 Technical Implementation

- **OOP Concepts**: Implemented **inheritance**, **encapsulation**, and **abstraction**.  
  Example: `Client`, `Employee`, and `Admin` classes inherit from a base `Person` class.
- **File Handling**: Persistent storage for client, employee, and admin data in text files (`Clients.txt`, `Employees.txt`, `Admins.txt`).
- **Data Structures**: Used `vector` for efficient data management and retrieval.
- **Validation Class**: Reusable validation methods for **name**, **password**, **balance**, and **salary**.
- **ASCII Art**: Custom console ASCII art for “Welcome” and “Bank System” screens for a better user experience.

---

## 📝 Phases of Development

1. **Core Classes**: Developed `Client`, `Employee`, and `Admin` with setters, getters, and validation.
2. **File Management**: Added file handling for storing/retrieving data with a dedicated `FileManager` class.
3. **User Interface**: Created a console-based menu system for **Client**, **Employee**, and **Admin** modules, including login/logout functionality.

---

## 💻 Tools & Technologies

- **C++**: Core programming language.
- **OOP**: Inheritance, encapsulation, and abstraction.
- **File Handling**: Persistent storage in text files.
- **Vectors**: Efficient data structures for managing records.
- **ASCII Art**: Console visuals for improved UX.

---

## 🎯 Learning Outcomes

This project allowed me to:
- Apply OOP principles in a real-world scenario.
- Implement file handling for persistent storage.
- Manage data efficiently using **vectors**.
- Develop problem-solving and debugging skills in **C++**.
- Build a modular and scalable console application.

