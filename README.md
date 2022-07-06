# django-todo
Simple Django todo list 
Add and delete functionality 

https://user-images.githubusercontent.com/86543368/173093235-72dbdd96-dc4d-4c46-b716-8b273b6bc8ff.mp4

Data stored in sqlite DB 

Django project structure
.
├── config
│   ├── config
│   │   ├── asgi.py
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   └── manage.py
└── .venv



*config/ is the external folder of your project. It doesn’t matter to Django, so you can actually rename it to whatever you want.

*config/config/ is the actual Django project folder. It contains the setting files of your project.

*manage.py is a Python script with the same functionality of django_admin but uses your project’s settings.
*__init__.py makes config/config a Python package.
*settings.py is the core file of your project. You can add, modify, or delete variables to change the behavior of your project.
*urls.py is the file that defines the URLs of your project.
*asgi.py and wsgi.py let you deploy your project to a server.

Command	Description
python -m venv (name_of_venv)	Creates a virtual environment
source (venv)/bin/activate	Activates a virtual environment
django-admin startproject (project_name)	Starts a Django project
django-admin startproject (project_name) .	Sets up a project in the same directory
python manage.py runserver	Runs the Django server
python manage.py startapp (app_name)	Creates a Django app

 



