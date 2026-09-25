# 🐍 Python Console Banking System

An interactive Python command-line (CLI) application simulating core banking operations. This project showcases Object-Oriented Programming (OOP) concepts, encapsulation, input validation, and robust control flow in Python.

---

## 🎯 Key Concepts & Features

* **Object-Oriented Programming (OOP):** Built using a structured `BankAccount` class.
* **Encapsulation:** Instance variables (`_balance`, `_account_number`, `_account_holder`) are protected with leading underscores and exposed safely using `@property` decorators for read-only access.
* **Variable Initialization:** Explicit declaration and initialization of attributes inside the `__init__` constructor method.
* **Interactive Control Flow:** Utilizes a `while True` loop to maintain an active terminal menu until gracefully terminated by the user.
* **Robust Input Validation:** Employs `try / except` exception handling (`ValueError`) to prevent application crashes when users enter non-numeric input.
* **Business Logic Checks:** Prevents negative deposits and ensures withdrawals cannot exceed the available balance.

---

## ⚙️ Menu Options & Functionality

1. **Display Status:** Shows current account holder details, account number, and balance.
2. **Deposit Funds:** Safely adds funds after validating that the amount is positive.
3. **Withdraw Funds:** Deducts funds after confirming sufficient account balance.
4. **Exit Program:** Terminates the main loop cleanly using `break`.

---

## 🚀 How to Run Locally

1. Prerequisites: Ensure you have **Python 3.x** installed.
2. Download or clone this repository.
3. Open your terminal in the project directory and run:
   ```bash
   python bank_application.py
