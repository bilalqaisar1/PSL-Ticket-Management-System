# PSL Ticket Management System 🏏
_A comprehensive system for managing PSL ticket bookings, fan registrations, and match schedules._

![PSL Logo](https://upload.wikimedia.org/wikipedia/en/thumb/2/21/Pakistan_Super_League_logo.svg/512px-Pakistan_Super_League_logo.svg.png)

## ✨ Overview
The **PSL Ticket Management System** allows users to:
- Book tickets for PSL matches \U0001F3DF️
- Check match schedules and stadium details \U0001F4C5
- Verify ticket validity ✅
- Manage fan registrations and purchase history \U0001F464
- Process refunds seamlessly \U0001F4B3

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

## 🖼️ Screenshots
| Ticket Booking | Match Schedule | Fan Management |
|---------------|----------------|----------------|
| ![Booking](https://via.placeholder.com/200x150) | ![Schedule](https://via.placeholder.com/200x150) | ![Fan](https://via.placeholder.com/200x150) |

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
\U0001F538 Found a bug or have a suggestion? [Open an issue](https://github.com/bilalqaisar1/PSL-Ticket-Management-System/issues).  
\U0001F538 Want to contribute? Fork the repo and submit a PR!  

📧 For inquiries, contact [Bilal Qaisar](mailto:muhammadbilalqaiar@gmail.com).

---

### ✨ Enjoy PSL Matches with Seamless Ticket Booking! 🏏\U0001F39F️

