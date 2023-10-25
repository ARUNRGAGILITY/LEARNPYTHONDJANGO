

# Basics: Setting up django

### Install Python
### Install pip
### Install pipenv

### Install git
### Steps
#### 1. Create a django directory say "D:/DJANGO"
#### 2. Create a particular Learning directory say cd D:\DJANGO, mkdir env_learn1
#### 3. pipenv shell
#### 4. pip install django==4.1 or simply pip install django for latest version
```pip install django```
####

django-admin startproject project_basics .
python manage.py makemigrations blog
python manage.py migrate
python manage.py runserver
python manage.py createsuperuser
