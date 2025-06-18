Company API (Django REST) 📈

A RESTful API backend for managing companies and their employees using Django and Django REST Framework.

🔎 Features

CRUD operations for Company and Employee models

REST API with proper status codes

Serializers and DRF views

SQLite/PostgreSQL support

⚡ Tech Stack

Python

Django

Django REST Framework

SQLite

✅ API Endpoints

Endpoint

Method

Description

/companies/

GET, POST

List or create company

/companies//

GET, PUT, DELETE

Detail or update company

/employees/

GET, POST

List or create employee

/employees//

GET, PUT, DELETE

Detail or update employee

🔧 Setup

pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

🌐 Docs

Swagger UI or Postman collection included for testing endpoints.

🎡 Possible Enhancements

JWT Authentication

Pagination, filtering, sorting

Frontend in React or Streamlit
