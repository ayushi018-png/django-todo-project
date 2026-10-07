# Simple Django To-Do Web App

A beginner-friendly Django project based on the **"ToDo webapp using Django"** project listed in the GeeksforGeeks Django Projects collection.

Reference:
https://www.geeksforgeeks.org/python/django-projects/

## What this project does

The application lets a user:

- Add a task
- See all tasks
- Mark a task as completed
- Delete a task

The project intentionally uses simple Django concepts so that every part can be explained during a class demonstration.

## Technologies

- Python
- Django
- SQLite
- HTML
- Basic CSS

## Main Django concepts used

- `models.py` - stores tasks in the SQLite database
- `forms.py` - creates the task form
- `views.py` - handles requests and uses `render()`
- `urls.py` - connects URLs to views
- Templates - display the web pages
- Django ORM - saves and retrieves task data

## Project structure

```text
django_todo_project/
├── manage.py
├── requirements.txt
├── README.md
├── .gitignore
├── todo_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
└── todo/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── forms.py
    ├── models.py
    ├── urls.py
    ├── views.py
    ├── migrations/
    │   └── __init__.py
    └── templates/
        └── todo/
            ├── home.html
            └── success.html
