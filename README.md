# Django-DRF-CRUD-Project
In this Repo I stored my both project Django-RestFramework Project and Django-CRUD-Operations-Project.
<br>

# Django CRUD + DRF API Project
<br>

A full-stack Django project demonstrating a CRUD application integrated with a Django REST Framework (DRF) backend API.
<br>

## Project Architecture
<br>

This repository follows a **monorepo structure** containing two independent Django projects:
<br>

- **CRUD Application** – Handles UI, forms, and user interactions<br>
- **DRF Backend API** – Provides RESTful APIs for data operations<br>
<br>

django-drf-crud-project/<br>
├── backend-api/ <br>      
├── crud-app/   <br>        
└── README.md  <br>
<br>

## How It Works
<br>
- The **DRF backend** exposes REST APIs for data operations  <br>
- The **CRUD application** consumes these APIs using the `requests` library  <br>
- This simulates a real-world frontend–backend architecture  <br>
<br>

## Tech Stack
<br>
- Python 3.11+<br>
- Django 5.x<br>
- Django REST Framework<br>
- SQLite (default)<br>
- Requests (API communication)<br>
- Git & GitHub
<br>

## Dependencies
<br>

Each project maintains its own dependencies:
<br>
- `backend-api/requirements.txt`<br>
- `crud-app/requirements.txt`
<br>

## Setup Instructions
<br>
### 1️⃣ Clone the Repository <br>
```bash <br>
git clone https://github.com/your-username/django-drf-crud-project.git<br>
cd django-drf-crud-project
<br>

cd backend-api<br>
python -m venv venv<br>
venv\Scripts\activate   # Windows<br>
pip install -r requirements.txt<br>
python manage.py migrate<br>
python manage.py runserver 8000
<br>

cd ../crud-app<br>
python -m venv venv<br>
venv\Scripts\activate<br>
pip install -r requirements.txt<br>
python manage.py migrate<br>
python manage.py runserver 8001
<br>

## Key Learnings
<br>

- Django project structuring<br>
- REST API development using DRF<br>
- API consumption using Python `requests`<br>
- Clean Git & GitHub workflow<br>
- Separation of concerns in backend systems
<br>

## Author
<br>

Samarth Deshmukhe <br>
BTech in AI & ML  <br>
Aspiring Backend / Python Developer
