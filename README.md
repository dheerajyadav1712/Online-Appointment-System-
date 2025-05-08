# 🏥 Online Doctor Appointment System

An advanced web-based application that allows patients to book appointments with doctors online. Built using **HTML, CSS, JavaScript**, **PHP**, and **MySQL**, and hosted on **WAMP server**. Designed for ease of use by **Patients, Doctors, and Admins**.

## 🚀 Features

### 👨‍⚕️ Patients
- Register and login
- View available doctors by specialty
- Book appointments
- View booking history and prescription
- Receive notifications (Email/SMS integration optional)

### 🩺 Doctors
- Register and login
- Set available days and time slots
- Approve/Reject appointments
- Upload prescription documents
- View patient history

### 🛠️ Admin
- Login to Admin Panel
- Manage doctors and patients
- View, approve, or delete appointments
- Generate reports and view analytics

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Server**: WAMP (Windows, Apache, MySQL, PHP)

## 🗃️ Database Structure (MySQL)

- `users`: Stores patients, doctors, and admin details
- `appointments`: Stores booking data
- `doctors`: Stores additional doctor info
- `prescriptions`: Prescription uploads for patients

## 📁 Project Structure

doctor-appointment/
├── index.php
├── login.php
├── register.php
├── dashboard.php
├── book_appointment.php
├── doctor_schedule.php
├── upload_prescription.php
├── view_appointments.php
├── admin/
│ ├── dashboard.php
│ ├── manage_users.php
│ └── manage_appointments.php
├── css/
├── js/
├── includes/
│ ├── db.php
│ ├── auth.php
│ └── functions.php
└── sql/
└── database.sql


## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dheerajyadav1712/doctor-appointment-system.git

2. Place the folder in your www directory (WAMP).
3. Import the database.sql file in phpMyAdmin to create necessary tables.
4. Configure database connection in includes/db.php.
5. Start WAMP and access:
  ```bash
http://localhost/doctor-appointment-system/
  ```


## 📸 Screenshots
![Screenshot (9)](https://github.com/user-attachments/assets/2fd5eae3-8072-4611-8db5-0cb42144d66a)

![Screenshot (6)](https://github.com/user-attachments/assets/0298bc3b-cc76-4e72-b3da-746e2f8d59b4)

![Screenshot (3)](https://github.com/user-attachments/assets/2732e325-00d2-4d7f-93d1-c6363b6d778a)


## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

**Developed by [Dheeraj Yadav](https://github.com/dheerajyadav1712)** ❤️
