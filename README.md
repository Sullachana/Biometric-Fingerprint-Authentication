# Biometric-Fingerprint-Authentication
Biometric Fingerprint Authentication for Student Attendance System using Visual Studio.Net and Arduino.

# Fingerprint Attendance System

This is a **biometric attendance system** developed using **C# in Visual Studio (.NET Framework)** integrated with an **Arduino-based fingerprint sensor** and **MySQL database** via **XAMPP**.

## 🛠️ Tech Stack

- **Frontend & App Logic:** C# (.NET Windows Forms)
- **Hardware Integration:** Arduino (via Arduino IDE)
- **Database:** MySQL (via XAMPP)
- **Communication:** Serial Communication (COM Port)

---

## 📂 Folder Structure

- `Attendance Monitoring With Fingerprint/` – Main Visual Studio project.
- `Fingerprint_Sensor/` – Arduino sketch for the fingerprint sensor.
- `Adafruit-Fingerprint-Sensor-Library-master/` – Required Arduino library.
- `attendancedb.sql` – Database schema and table creation script.
- `Circuit Diagram.png` – Wiring layout for connecting fingerprint sensor.
- `MySql.Data.dll` – MySQL connector library for .NET.

---

## 🔧 Setup Instructions

### 1. Arduino Setup
- Open the `Fingerprint_Sensor` sketch in **Arduino IDE**.
- Install the **Adafruit Fingerprint Sensor Library** (or copy from `Adafruit-Fingerprint-Sensor-Library-master/`).
- Connect the fingerprint module as per `Circuit Diagram.png`.
- Upload the code to your Arduino board.

### 2. MySQL Database Setup
- Open **XAMPP**, start **Apache** and **MySQL**.
- Use **phpMyAdmin** or CLI to import the database:
  ```sql
  CREATE DATABASE attendancedb;
  USE attendancedb;
  SOURCE attendancedb.sql;
  
3. Visual Studio Setup
Open Attendance Monitoring With Fingerprint.sln in Visual Studio.

Restore or reference MySql.Data.dll in your project references.

Ensure the correct COM port is used in your C# code for Arduino connection.

Run the project.

✅ Features
Fingerprint-based attendance marking.

Real-time attendance recording to MySQL database.

Simple circuit with Arduino and sensor module.

User-friendly desktop interface.

📷 Screenshots & Circuit

📜 License
This project is open-source and available for free use, modification, and distribution.

🤝 Contributing
Feel free to fork the repo and submit pull requests!
