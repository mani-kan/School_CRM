# 🏫 School CRM Management System

A **Full Stack Web Application** built using **Python & Django** to help schools efficiently manage teacher information. This system allows administrators to add, view, update, and delete teacher records through a user-friendly interface.

---

## 🚀 Features

✅ **Admin Authentication** – Secure login system  
👩‍🏫 **Teacher Management** – Add, Edit, View & Delete teacher details  
🔍 **Search & Filter** – Quickly find teacher information  
📊 **Dashboard Overview** – Organized data management  
🛠️ **Django Admin Customization**  
🧾 **Data Validation & Error Handling**  

---

## 🧠 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | HTML, CSS, Bootstrap |
| Backend | Python, Django |
| Database | SQLite / MySQL |
| Version Control | Git & GitHub |

---

## 📂 Project Structure

School_CRM/
│── crm_app/ # Django app for handling teacher data
│── school_crm/ # Project core settings & URLs
│── templates/ # HTML Templates (Frontend)
│── static/ # CSS, JS, Images
│── db.sqlite3 # Database
│── manage.py
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

Follow the steps to run this project on your system:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/School_CRM.git
cd School_CRM
2️⃣ Create a Virtual Environment

python -m venv venv
venv\Scripts\activate   # For Windows
3️⃣ Install Dependencies

pip install -r requirements.txt
4️⃣ Apply Migrations

python manage.py makemigrations
python manage.py migrate
5️⃣ Start the Server

python manage.py runserver
Now open the browser and visit:
👉 http://127.0.0.1:8000/

🔐 Superuser (Admin Access)
Create a superuser to access the Django Admin Panel:

bash
Copy code
python manage.py createsuperuser
Admin Panel URL:
👉 http://127.0.0.1:8000/admin/


Example:

Dashboard	Teacher List
(screenshot)	(screenshot)

📈 Future Enhancements
🔹 Student Management Module
🔹 Fee & Attendance Tracking
🔹 Export Data to Excel / PDF
🔹 Email & Notification System
🔹 Role-Based Access (Admin/Staff)

🧑‍💻 Author
Your Name
📍 Python Full Stack Developer

If you like this project, don't forget to ⭐ star the repo!

