# Capstone Project - Backend

This project is the backend for the Capstone Project, built with Django and Django REST framework.

## Prerequisites

- Python 3.x
- pip (Python package installer)
- Virtualenv (optional but recommended)

## Setting Up the Backend

```bash
### 1. Clone the Repository

git clone https://github.com/yourusername/capstone_project.git
cd capstone_project/backend


### 2. Set Up Virtual Env

python3 -m venv env
source env/bin/activate (mac)
env\Scripts\activate (windows)


### 3. Install dependencies

pip install -r requirements.txt


### 4. Apply Migrations

python manage.py makemigrations
python manage.py migrate

### 5. Create Superuser
python manage.py createsuperuser

### 6. Run dev server
python manage.py runserver

(should be at http://127.0.0.1:8000/)


