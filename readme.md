# LittleLemonBookingSystem
# 🍋 Little Lemon Booking System

This project implements a database-backed booking system for **Little Lemon**, a fictional restaurant. It includes database procedures, Python scripts, and visual data analysis using Tableau.

## 📦 Project Structure
LittleLemonBookingSystem/
├── ER_Diagram.png
├── littlelemon_schema.sql
├── procedures/
│ ├── AddBooking.sql
│ ├── CancelBooking.sql
│ ├── GetMaxQuantity.sql
│ ├── ManageBooking.sql
│ └── UpdateBooking.sql
├── python_scripts/
│ ├── db_connect.py
│ └── trigger_listener.py
├── Tableau/
│ └── LittleLemonDashboard.twbx
├── test_data/
│ └── LittleLemon_data.xlsx
└── README.md

---

## ⚙️ Features

### ✅ MySQL Database
- Database schema for bookings and customer management.
- Foreign keys for relational integrity.
- Pre-loaded sample data for testing.

### ✅ Stored Procedures
- `AddBooking()`: Add a new booking.
- `UpdateBooking()`: Update existing booking.
- `CancelBooking()`: Cancel a booking.
- `ManageBooking()`: Logic wrapper for booking tasks.
- `GetMaxQuantity()`: Returns the maximum quantity per booking.

### ✅ Python Integration
- `db_connect.py`: Connects Python to MySQL.
- `trigger_listener.py`: Monitors and reacts to data changes (basic trigger simulation).

### ✅ Tableau Dashboard
Interactive dashboard created in Tableau that includes:
- Bookings Over Time
- Most Reserved Tables
- Customer Counts by Month
- Peak Booking Hours
- KPI summaries (Total Bookings, Active Customers)

---

## 📊 Screenshots

> Include screenshots of your ER Diagram and Tableau Dashboard here.

---

## 🧪 How to Run the Project

### 1. Set up MySQL

```sql
SOURCE littlelemon_schema.sql;


Peer Review Checklist
 GitHub repo created and organized

 ER Diagram included

 All procedures implemented

 Python scripts included

 Tableau dashboard saved as .twbx

 Sample data included


---

Let me know if you want to personalize it with your name or add screenshots automatically.
