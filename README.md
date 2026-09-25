# kivy-mysql-auth-system
A cross-platform GUI authentication system built with Python, Kivy, and MySQL featuring user registration, session management, and credential validation.
# Python Kivy MySQL Authentication System

A secure, desktop-based user authentication and dashboard system built using **Python**, the **Kivy** framework, and a **MySQL** database managed via **XAMPP**. 

This application provides a smooth multi-screen workflow allowing users to register, log in, and view a personalized session-managed dashboard.

---

## Features

* **User Registration:** Validates empty input fields, ensures password matching, and prevents duplicate username entries[cite: 1].
* **User Authentication:** Verifies registered credentials against the MySQL database securely[cite: 1].
* **Session Dashboard:** Displays a personalized welcome message and email details upon successful login, with a functional logout mechanism[cite: 1].
* **Database Integration:** Connects seamlessly with local MySQL databases using `mysql-connector-python`[cite: 1].

---

## Tech Stack

* **Language:** Python[cite: 1]
* **GUI Framework:** Kivy[cite: 1]
* **Database/Server:** MySQL via XAMPP[cite: 1]
* **Database Connector:** `mysql-connector-python`[cite: 1]

---

## Prerequisites & Installation

1. **Install XAMPP:** Download and run XAMPP, then start the **Apache** and **MySQL** modules from the control panel.
2. **Install Python Libraries:** Open your terminal and install Kivy and the MySQL connector:
   ```bash
   pip install kivy mysql-connector-python
