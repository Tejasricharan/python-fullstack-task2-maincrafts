# python-fullstack-task2-maincrafts
Project Overview

This project implements a User Authentication System using Flask, allowing users to Register, Login, and Logout securely. It demonstrates the fundamentals of authentication, session management, and password security in a Flask web application.

Technologies Used:

Python

Flask

SQLite (Database)

HTML & CSS

Werkzeug Security

Flask Sessions

Features:

User Registration with secure password hashing

User Login with session management

User Logout functionality

Protected Dashboard (accessible only after login)

Flash messages for user feedback

Project Structure:
project/
│── app.py
│── database.db
│── templates/
│   ├── register.html
│   ├── login.html
│   ├── dashboard.html
│── static/
│── README.md

Authentication Flow:

Registration:

User submits username & password

Password is hashed using Werkzeug

User details are stored in the database

Login:

User enters credentials

Password is verified against the hashed password

Session is created upon successful login

Dashboard:

Accessible only when the user is logged in

Session validation is checked before rendering

Logout:

Session is cleared

User is redirected to the login page
