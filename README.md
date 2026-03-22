🫀 Organ Donation Management System

A desktop-based application built using Python (Tkinter) and MySQL to manage organ donation registration and donor details efficiently.

📌 Project Overview

This project allows users to:

Register as an organ donor
Select the organ they wish to donate
Login securely
Provide detailed medical and personal information
Store all data in a MySQL database

The system is designed with a simple and user-friendly GUI using Tkinter.

🚀 Features

✅ Donor Registration Form
✅ Organ Selection (Heart, Kidney, Liver)
✅ Login Authentication UI
✅ Image Display based on selected organ
✅ User Details Form (Health & Lifestyle Info)
✅ MySQL Database Integration
✅ Error Handling & Validation
✅ Multi-window GUI Navigation

🖥️ Technologies Used
Python
Tkinter (GUI)
Pillow (Image Processing)
PyMySQL (Database Connectivity)
MySQL
🗂️ Database Structure
1. donor Table
Field	Type
id	INT (Primary Key)
name	VARCHAR
age	INT
organ	VARCHAR
2. user_details Table
Field	Type
id	INT (Primary Key)
name	VARCHAR
age	INT
weight	FLOAT
height	FLOAT
blood_group	VARCHAR
disability	VARCHAR
habit	VARCHAR
health_issues	VARCHAR
operations	VARCHAR
⚙️ Installation & Setup
Clone the repository:
git clone https://github.com/your-username/organ-donation-system.git
Install required libraries:
pip install pillow pymysql
Setup MySQL:
Create database: organ_db
Create tables using provided SQL queries
Update database credentials in code:
user="root"
password="your_password"
Run the project:
python main.py
📸 Screenshots
Donor Registration Form
Login Page
Organ Image Display
User Details Form

(Add screenshots here for better presentation)

🔮 Future Enhancements
🔐 Secure login with database authentication
📊 Admin dashboard to view donors
📁 Export data to PDF/Excel
🌐 Web-based version using Django/Flask
📱 Mobile app integration
👨‍💻 Author

Abi
Passionate Python Developer 🚀

⭐ Support

If you like this project:
👉 Give it a ⭐ on GitHub
👉 Share with others
