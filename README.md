Django Blog Application

Introduction:

This is a simple Django Blog Application that allows users to create, edit, and delete blog posts. It demonstrates the basic CRUD operations using Django's MVT architecture.

Features:

Create new blog posts
Edit existing blog posts
Delete blog posts
View a list of all blog posts
View details of individual blog posts

Requirements:

Python 3.6+
Django 3.0+
SQLite (default database for Django)

Installation:

Clone the repository:

bash
git clone https://github.com/yourusername/django-blog-app.git
cd django-blog-app

Create a virtual environment and activate it:

bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

Install the required packages:

bash
pip install -r requirements.txt

Apply migrations:

bash
python manage.py migrate

Create a superuser (optional, for admin access):

bash
python manage.py createsuperuser

Run the development server:

bash
python manage.py runserver

Open your web browser and go to http://127.0.0.1:8000 to see the blog application.

CSS Styling:
The application uses a basic CSS stylesheet for styling, located at blog/static/blog/styles.css. You can customize this file to update the appearance of your blog application.

License:
This project is licensed under the MIT License - see the LICENSE file for details.
 
