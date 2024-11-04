
## Title -  Task management Application

## Description
A simple and user-friendly To-Do List application built with Python and Flask. The application allows users to manage their tasks with full CRUD (Create, Read, Update, Delete) functionality. It includes features like responsive design, and efficient data management.

## Features
- Database management app for daily activities.
- Allows users to add, update, and delete tasks.
- Responsive front-end using Bootstrap.
- Error handling for smooth user experience.
- Offers a straightforward user experience for organizing daily activities.

## Technologies
- Backend: Flask, Flask-SQLAlchemy, Flask-Migrate
- Frontend: HTML, CSS, Bootstrap
- Database: SQLite (or replace with PostgreSQL/MySQL if desired)

## Installation

Prerequisites
- Python 3.7+
- Git (optional, for cloning the repository)

Steps

1 . Clone the repository :
    
  git clone https://github.com/vinodkumarkuruva/Todo_Application_Flask.git
  cd Todo_Application_Flask

2 . Create a virtual environment :

  python -m venv venv
  venv\Scripts\activate - To activate virtual environment

3 . Install dependencies :

  pip install -r requirements.txt

4 . Set up the Database :
  
  flask db init
  flask db migrate -m "Initial migration."
  flask db upgrade

5 . Run the application :

Python app.py 

The application will be accessible at http://127.0.0.1:5000.

## Documentation

[Python_Documentation](https://docs.python.org/3/)

[Flask_Documentation](https://flask.palletsprojects.com/en/stable/)

[SQLite_Documentation](https://www.sqlite.org/docs.html)

[Bootstrap_Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)



