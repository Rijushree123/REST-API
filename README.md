# 🚀 Django REST API – Employee Management System

A **RESTful API built using Django and Django REST Framework (DRF)** to perform **CRUD operations** on Employee data.

---

## ✨ Features
- Create employee
- Read employee(s)
- Update employee
- Delete employee
- RESTful URL design
- JSON responses

---

## 🛠 Tech Stack
- **Python 3**
- **Django**
- **Django REST Framework**
- **SQLite**
- **Git & GitHub**

---

## 📂 Project Structure
```text
REST-API/
├── restproject/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── employeeapp/
│   ├── models.py
│   ├── serializers.py
│   ├── views.py
│   └── urls.py
├── db.sqlite3
├── manage.py
└── README.md
```
## ⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Rijushree123/REST-API.git
cd REST-API

## 2️⃣ Create Virtual Environment
python -m venv venv


Activate it:

venv\Scripts\activate

## 3️⃣ Install Dependencies
pip install django djangorestframework

## 4️⃣ Run Migrations
python manage.py makemigrations
python manage.py migrate

## 5️⃣ Run Server
python manage.py runserver

## 🔗 API Endpoints
| HTTP Method | Endpoint              | Description             |
| ----------- | --------------------- | ----------------------- |
| GET         | `/employees/`         | Get all employees       |
| POST        | `/employees/`         | Create new employee     |
| GET         | `/employees/{empId}/` | Get employee by ID      |
| PUT         | `/employees/{empId}/` | Update full employee    |
| PATCH       | `/employees/{empId}/` | Update partial employee |
| DELETE      | `/employees/{empId}/` | Delete employee         |

📌 Sample Request (POST)
{
  "name": "John Doe",
  "email": "john@example.com",
  "position": "Developer",
  "salary": 50000
}

## 👩‍💻 Author

Rijushree Guha
🔗 GitHub: https://github.com/Rijushree123

Rijushree Guha
🔗 GitHub: Rijushree123

⭐ Support

If you like this project, give it a star ⭐
