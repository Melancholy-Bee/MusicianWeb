# MusicianWeb
This is my final project for COSC 2418. It is a web app for string musicians where you can post to a forum page and give comments to others. 

Features: 
Make an account, 
Login, 
Edit profile, 
Create posts, 
Add comments

Bugs: 
Images not added when creating a post, 
Sign-in with Github and Google not working, dead linked, 
Password change at sign-in page not working, dead linked, 

Goals: 
Fix bugs, 
Add options to upload videos and audio, 
Show comments on posts, 
Click on posts to take you to a separate webpage where you can add comments and view the post

Installation: 
NOTE: The following instructions are for a Unix OS. For Windows instructions and help, visit https://www.w3schools.com/django/django_getstarted.php
- Set up a virtual environment
    - python -m venv <name of environment>
- Activate environment
    - source <name of environment>/bin/activate
- Install Django
    - python -m pip install Django
- Start project
    - django-admin startproject MusicianWeb
- Create app
    - python manage.py startapp strings
- Copy files into the project directory
- Make migrations
    - python manage.py makemigrations
    - python manage.py migrate
- Run project
    - python manage.py runserver

For anyone who wants to create the login pages, visit this website: https://dev.to/earthcomfy/creating-a-django-registration-login-app-part-i-1di5
