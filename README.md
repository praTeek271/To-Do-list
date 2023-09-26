# To-Do List Web Application with Django and User Authentication
[![Django CI](https://github.com/praTeek271/To-Do-list/actions/workflows/django.yml/badge.svg?branch=main)](https://github.com/praTeek271/To-Do-list/actions/workflows/django.yml)
### Link ::  https://github.com/praTeek271/To-Do-list
## Overview

This project is a To-Do List web application built using the Django web framework with user authentication. It allows users to create, manage, and organize their tasks in a user-friendly interface. The application includes features for user registration, login, and password reset.


## Table of Contents

1. [Requirements](#requirements)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [File Structure](#file-structure)
6. [Contributing](#contributing)
7. [License](#license)

## Requirements

- Python 3.8+
- Django 3.2+
- HTML and CSS knowledge for frontend customization

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/todo-list-django.git
   ```

2. Change into the project directory:

   ```bash
   cd todo-list-django
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Create the database tables:

   ```bash
   python manage.py migrate
   ```

7. Create a superuser account for admin access:

   ```bash
   python manage.py createsuperuser
   ```

8. Start the development server:

   ```bash
   python manage.py runserver
   ```

9. Access the application in your web browser at `http://127.0.0.1:8000/`.

## Usage

1. Register a new account or log in with an existing account.
2. Once logged in, you can:
   - Create new tasks.
   - Mark tasks as completed.
   - Delete tasks.
   - Edit task details.
   - Log out when you're done.

## Features

- User authentication: Register, log in, and reset your password.
- Create new tasks with due dates and descriptions.
- Mark tasks as completed to keep track of your progress.
- Edit or delete tasks to stay organized.
- User-friendly and responsive HTML/CSS frontend.

## File Structure

```
├───base
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── __init__.py
│
├───migrations
│   ├── 0001_initial.py
│   ├── 0002_auto_20210322_2234.py
│   └── __init__.py
│   └── __pycache__
│       ├── 0001_initial.cpython-38.pyc
│       ├── 0002_auto_20210322_2234.cpython-38.pyc
│       └── __init__.cpython-38.pyc
│
├───templates
│   └───base
│       ├── login.html
│       ├── main.html
│       ├── register.html
│       ├── task.html
│       ├── task_confirm_delete.html
│       ├── task_form.html
│       └── task_list.html
│
└───__pycache__
    ├── admin.cpython-38.pyc
    ├── apps.cpython-38.pyc
    ├── forms.cpython-38.pyc
    ├── models.cpython-38.pyc
    ├── urls.cpython-38.pyc
    ├── views.cpython-38.pyc
    └── __init__.cpython-38.pyc

└───todo_list
    ├── asgi.py
    ├── settings.py
    ├── urls.py
    ├── wsgi.py
    └── __init__.py
    └── __pycache__
        ├── settings.cpython-38.pyc
        ├── urls.cpython-38.pyc
        ├── wsgi.cpython-38.pyc
        └── __init__.cpython-38.pyc

```

## Contributing

Contributions to this project are welcome. Feel free to open issues, submit pull requests, or suggest new features or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy using your To-Do List web application with Django and User Authentication! If you have any questions or run into any issues, please don't hesitate to contact us.
