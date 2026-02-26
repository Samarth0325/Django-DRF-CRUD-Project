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
- **CRUD Application** – Handles UI, forms, and user interactions
- **DRF Backend API** – Provides RESTful APIs for data operations
<br>
django-drf-crud-project/
├── backend-api/       
├── crud-app/           
└── README.md
<br>
## How It Works
<br>
- The **DRF backend** exposes REST APIs for data operations
- The **CRUD application** consumes these APIs using the `requests` library
- This simulates a real-world frontend–backend architecture
<br>
## Tech Stack
<br>
- Python 3.11+
- Django 5.x
- Django REST Framework
- SQLite (default)
- Requests (API communication)
- Git & GitHub
<br>
## Dependencies
<br>
Each project maintains its own dependencies:
<br>
- `backend-api/requirements.txt`
- `crud-app/requirements.txt`
<br>
## Setup Instructions
<br>
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/django-drf-crud-project.git
cd django-drf-crud-project
<br>
cd backend-api
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver 8000
<br>
cd ../crud-app
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver 8001
<br>
## Key Learnings
<br>
- Django project structuring
- REST API development using DRF
- API consumption using Python `requests`
- Clean Git & GitHub workflow
- Separation of concerns in backend systems
<br>
## Author
<br>
Samarth Deshmukhe 
BTech in AI & ML  
Aspiring Backend / Python Developer