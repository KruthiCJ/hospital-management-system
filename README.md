# Hospital Management System 🏥

A web-based system designed to streamline hospital operations such as patient registration, appointment scheduling, staff management, and medical record tracking. Built with a clean UI and role-based access control for staff and admin.

---

## 🔧 Tech Stack:
- HTML5
- CSS3
- JavaScript
- PHP
- MySQL

---
---

## ▶️ How to Run:
1. Install XAMPP or WAMP (for PHP + MySQL backend)
2. Place project folder inside `htdocs` (XAMPP) or `www` (WAMP)
3. Start Apache and MySQL servers
4. Import `hospital_db.sql` into phpMyAdmin
5. Open `localhost/hospital-management-system/index.php` in browser

---

## 💡 Features:
- Patient registration and login
- Admin dashboard for hospital operations
- Doctor/staff scheduling system
- Medical records and appointments
- Responsive design for tablet/desktop

---

## 📂 Folder Structure:
hospital-management-system/
│
├── index.php
├── login.php
├── dashboard/
│ ├── admin.php
│ └── doctor.php
├── assets/
│ ├── css/
│ ├── js/
│ └── images/
├── db/
│ └── connection.php
└── hospital_db.sql
