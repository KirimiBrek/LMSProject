<p align="center">
    <img src="./static/images/lib4.jpg" alt="Verbyl-Logo" height="170">
  <h3 align="center"><b>LMSProject</b></h3>

LMSProject, a web app made in Django, is an online library management system created as an at ease management of operations of small scaled libraries.

# Problem Statement

- File lost/damaged
- Difficult to search record
- Cost/space consuming

# Overview

## Purpose

LMSProject is an application which refers to library systems which are generally small or medium in size. It is used by librarian/students to access the library using a computerized system. Book/student maintenance modules are also included in this system which would keep track of the students using the library and also a detailed description about the books a library contains.

## Objective

- Improvement in control and performance
- Save cost/time

# Tech-Stack

<a href= "https://html.com" target="_blank"> <img src ='https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/html.svg' alt="html" width="50" height="55"> </a>
<a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank"> <img src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/css.svg" alt="php/mysql" width="50" height="55"/></a>
<a href="https://www.djangoproject.com" target="_blank"> <img src="https://www.opengis.ch/wp-content/uploads/2020/04/django-python-logo-e1588009010920.png" alt="python/django" width="60" height="65"/></a>
<a href="https://www.sqlite.org" target="_blank"> <img src="https://www.nuget.org/profiles/SQLite/avatar?imageSize=512" alt="sqlite" width="60" height="56"/></a>

# Features(Student Module)

- Register/Login
- View account dashboard.
- View available books in the library, issued book and book return date-time.
- Update profile.

# Features(Admin Module)

- Admin Dashboard
- Add/Manage authors, books, category of books,book fees
- Issue a new book to student, notifying students about the return date-time details
- Search student by student ID, view student details

# How To Run The Project?

To run this project, you must have installed <a href= "https://www.python.org/" target="_blank">Python</a> on your PC. After downloading the project, follow the steps below:

Step-1: Extract/unzip the file

Step-2: Go inside the project folder, open cmd and type the following commands to install Django Framework and run the webserver:

        pip install -r requirements.txt
        python manage.py runserver

Step-3: Finally, open the browser and go to localhost:8000
