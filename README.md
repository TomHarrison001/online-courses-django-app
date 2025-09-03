# Online Course Django App

This is an application built using:

- Python
- Django

## Features

- Authentication and authorisation
- Responsive pages
- Page views

## Get started

1. Clone repository
2. Set up virtual environment:
```
pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
```
3. Install dependencies `pip install -U -r requirements.txt`
4. Create initial migrations:
```
python3 manage.py makemigrations
python3 manage.py migrate
```
5. Run the server `python3 manage.py runserver`
6. Open http://localhost:8000/onlinecourse to view the app in web mode

## 📹 Screenshots

![Screenshot](/screenshot.png)
