# 🩸 Blood Bank Management System

## 📌 Project Overview
The **Blood Bank Management System** is a web-based application designed to facilitate the management of blood donation and distribution efficiently. This system allows donors to register and update their profiles, enables hospitals to request blood, and provides administrators with a centralized system for tracking blood availability.

## 🎯 Features
- **🩸 Donor Registration & Management**: Users can register as donors, update their details, and track their donation history.
- **🏥 Blood Request & Management**: Hospitals can request blood, and the system will match the availability.
- **📊 Inventory Management**: Real-time tracking of blood stock levels.
- **👥 User Roles**:
  - **🩸 Donor**: Register, donate, and view donation history.
  - **🔧 Administrator**: Manage donors, blood stocks, and requests.
  - **🏥 Hospital/Recipient**: Request blood as per requirement.
- **🔔 Notification System**: Alerts and notifications for blood request approvals and availability.
- **🔒 Secure Authentication**: Secure login system for users and administrators.

## 🛠 Technologies Used
- **🎨 Front-End**: HTML, CSS, JavaScript
- **🐍 Back-End**: Python (Django framework)
- **🗄 Database**: MySQL
- **🖥 Other Technologies**: Bootstrap for responsive design, Django ORM for database management

## 🚀 Installation Guide
### ✅ Prerequisites
Ensure you have the following installed:
- 🐍 Python 3.7+
- 🌍 Django 4.0.4
- 🗄 MySQL
- ⚡ XAMPP (for database management)

### 📌 Steps to Install & Run
1. **Clone the Repository**:
   ```bash
   git clone Blood-Bank-Management-System.git
   cd Blood-Bank-Management-System
   ```
2. **Create a Virtual Environment**:
   ```bash
   python -m venv env
   source env\Scripts\activate
   ```
3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Set Up Database**:
   - Start MySQL Server using XAMPP
   - Create a database named `blood_bank`
   - Run migrations:
     ```bash
     python manage.py makemigrations
     python manage.py migrate
     ```
5. **Run the Server**:
   ```bash
   python manage.py runserver
   ```
   Access the application at `http://127.0.0.1:8000/`

## 📖 Usage Guide
- **📝 Register/Login**: Users can create an account or log in.
- **🩸 Donate Blood**: Donors can register and schedule blood donation.
- **🔍 Request Blood**: Hospitals can search for available blood types and make requests.
- **📊 Manage Inventory**: Administrators can monitor blood stock levels and manage donors.


