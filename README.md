### django-api

## Installation
Windows
```
python -m venv env
// powershell
./env/Scripts/Activate 

pip install Django==3.2.4
pip install psycopg2

django-admin startproject project_api
django-admin startapp api

python manage.py createsuperuser

python manage.py makemigrations
python manage.py migrate
```

## Python list
companies = list(Company.objects.values())




