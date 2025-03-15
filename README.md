# PSL Ticket Management System 🏏
_A comprehensive system for managing PSL ticket bookings, fan registrations, and match schedules._

## ✨ Overview
The **PSL Ticket Management System** allows users to:
- Book tickets for PSL matches
- Check match schedules and stadium details
- Verify ticket validity ✅
- Manage fan registrations and purchase history 
- Process refunds seamlessly 

This system is built using **Python**, **SQLite**, and **Tkinter** for an interactive GUI.

---

## ✨ How to Run the Project
Follow these simple steps to get started:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/bilalqaisar1/PSL-Ticket-Management-System.git
cd PSL-Ticket-Management-System
```

### 2️⃣ Install Dependencies
Ensure you have Python installed (`>=3.7`). Install required libraries:
```bash
pip install sqlite3 tkinter
```

### 3️⃣ Set Up the Database
Run the following script to initialize the database:
```bash
python database_connect.py
```

### 4️⃣ Launch the Application
Once the database is created, start the GUI:
```bash
python front_end.py
```

---

## ✨ Features
### 🎟️ Ticket Management
- View available tickets
- Check ticket validity
- Purchase and refund tickets

### 📅 Match Management
- View PSL match schedules
- Get match details by ticket or match ID
- Check stadium details and seating capacity

### 👤 Fan Management
- Register new fans
- Retrieve fan details using CNIC or Fan ID
- View fan purchase history

### 💳 Payment Methods Supported
- **Bank Transfer**
- **Debit Card**
- **JazzCash**

---

## ✨ Project Structure
```
📦 PSL-Ticket-Management-System
 ┣ 📜 database_connect.py  # Initializes database and populates sample data
 ┣ 📜 back_end.py          # Handles database queries and business logic
 ┣ 📜 front_end.py         # GUI built with Tkinter for user interaction
 ┣ 📜 README.md            # Documentation (this file)
```

---

## ✨ Contributions & Issues
 Found a bug or have a suggestion? [Open an issue](https://github.com/bilalqaisar1/PSL-Ticket-Management-System/issues).  
 Want to contribute? Fork the repo and submit a PR!  

📧 For inquiries, contact [Bilal Qaisar](mailto:muhammadbilalqaiar@gmail.com).

---

### ✨ Enjoy PSL Matches with Seamless Ticket Booking! 🏏

