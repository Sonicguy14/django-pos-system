# Django POS System
A Point of Sale system built with Django featuring role-based access for admin, manager, and teller users.

## Features
- User authentication with different roles
- Admin user management
- Manager product management and sales reports
- Teller POS system with transaction processing
- Responsive web interface

## Installation
1. Clone the repository
2. Create virtual environment: python -m venv env
3. Activate environment:  
   - Linux/Mac: source env/bin/activate  
   - Windows: env\Scripts\activate
4. Install requirements: pip install -r requirements.txt
5. Run migrations: python manage.py migrate
6. Create superuser: python manage.py createsuperuser
7. Run server: python manage.py runserver

## Technology Stack
- Django
- SQLite (configurable for other DBs)
- HTML/CSS/JavaScript

