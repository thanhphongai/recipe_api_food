# Recipe API

### Technology

- python 3
- django 3
- django rest framework
- postgres

### Development

Install postgres:
    
Install python dependencies:

    pip install -r requirements.txt
    
Create database and tables:
    python manage.py makemigrations
    python manage.py migrate    

Create cache tables:

    python manage.py createcachetable 
    
Create superuser for admin:

    python manage.py createsuperuser
        
Run web server:    
    
    python manage.py runserver
    
URL: http://localhost:8000

