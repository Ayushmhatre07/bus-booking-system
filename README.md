# 🚌 Bus Booking System – PHP Web App

**Bus Booking System** is a web-based application developed in **PHP** that allows users to book bus tickets, and administrators to manage bus schedules, users, and locations. This project is ideal for learning PHP CRUD operations, session management, and admin-user workflows.

---

## 📌 Project Features

### 👤 User Side
- View available buses and schedules
- Book bus tickets
- View booked tickets

### 🛠️ Admin Side
- Manage users
- Add/edit/delete buses
- Set schedules and locations
- Monitor bookings

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript (basic)
- **Backend**: PHP
- **Database**: MySQL
- **Server**: Apache (via XAMPP/WAMP)

---

## ⚙️ Installation Instructions

### 🖥️ Prerequisites

- Install [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/)
- Enable Apache and MySQL modules

###   Project Structure
```
bus-booking-system-main/
├── index.php                  # Entry point
├── admin.php                 # Admin dashboard
├── book_now.php              # User ticket booking
├── manage_*.php              # Admin management files (bus, schedule, user, location)
├── db_connect.php            # Database connection settings
├── login_auth.php            # User authentication logic
├── home.php, navbar.php      # User interface files
├── *.PNG                     # UI assets
└── Readme.txt                # Legacy notes
```
### 🔧 Setup Steps

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/Ayushmhatre07/bus-booking-system-main.git
