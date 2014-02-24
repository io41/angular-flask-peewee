# AngularJS + Flask Boilerplate App

Changed this so that this works with Peewee instead of SQLAlchemy. 

A template for building apps with an Angular frontend and a Flask / python backend.

### How to Get Started

1. clone this repo

2. install all the necessary packages (best done inside of a virtual environment)
> pip install -r requirements.txt

3. run the app
> python runserver.py

4. create and seed the db (the server must still be running, so open a new terminal window first)
> python manage.py create_db && python manage.py seed_db

5. check out your blog
> http://localhost:5000/blog

6. if you like this project, give it a star :)
