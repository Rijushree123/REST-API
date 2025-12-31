🚀 Django REST API – Employee Management System

This project is a RESTful API built using Django and Django REST Framework (DRF) that performs CRUD operations (Create, Read, Update, Delete) on Employee data.

It is designed to demonstrate backend API development, clean architecture, and REST principles.

📌 Features

Create a new employee

Get all employees

Get employee by ID

Update employee details (PUT / PATCH)

Delete an employee

JSON-based API responses

Uses Django REST Framework

🛠 Tech Stack

Backend: Django

API Framework: Django REST Framework (DRF)

Database: SQLite (default)

Language: Python 3

Version Control: Git & GitHub

📂 Project Structure
REST-API/
│
├── restproject/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── employeeapp/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── serializers.py
│   ├── views.py
│   └── urls.py
│
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md

🔧 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Rijushree123/REST-API.git
cd REST-API

2️⃣ Create Virtual Environment
python -m venv venv


Activate it:

Windows

venv\Scripts\activate


Mac/Linux

source venv/bin/activate

3️⃣ Install Dependencies
pip install django djangorestframework

4️⃣ Run Migrations
python manage.py makemigrations
python manage.py migrate

5️⃣ Start the Server
python manage.py runserver


Server will run at:

http://127.0.0.1:8000/

🔗 API Endpoints
🔹 Base URL
http://127.0.0.1:8000/api/employees/

📥 Create Employee

POST

/api/employees/


Request Body (JSON):

{
  "name": "John Doe",
  "email": "john@example.com",
  "designation": "Software Engineer",
  "salary": 60000
}

📤 Get All Employees

GET

/api/employees/

📤 Get Employee by ID

GET

/api/employees/?id=1


OR (Recommended REST style)

/api/employees/1/

✏️ Update Employee (Full Update)

PUT

/api/employees/?id=1

✏️ Update Employee (Partial Update)

PATCH

/api/employees/?id=1

❌ Delete Employee

DELETE

/api/employees/?id=1

🧠 Concepts Used

RESTful API design

Django Models

DRF Serializers

Function-based views (@api_view)

HTTP methods (GET, POST, PUT, PATCH, DELETE)

Status codes

Query parameters

🎯 Future Improvements

JWT Authentication

Pagination & Filtering

PostgreSQL database

Swagger / OpenAPI documentation

Deployment (AWS / Render)

👩‍💻 Author

Rijushree Guha
🔗 GitHub: Rijushree123

⭐ Support

If you like this project:

⭐ Star the repository

🍴 Fork it

🧠 Learn & build more APIs!
