# CAT2API
# Django E-Commerce Application
This project is a Django-based e-commerce application that manages Customers and their Orders. It demonstrates Django's ORM capabilities by defining and managing relationships between models.
 
# Project Overview 
This Django project models a basic e-commerce system where:
- Customers can place multiple orders.
- Orders are linked to a single customer.
- Each order contains details like the date and total amount.

## Setup Instructions

# 1. Clone the Repository

git clone "https://github.com/Dexecuting/CAT2API.git"

# Creating a virtual environment
python -m venv .venv #Creating a virtual environment
CMD .\.venv\Scripts\activate.bat #Activating a virtual environment

# Installing Django
pip install django

# Creating a project 
django-admin startproject CAT2project

# Apply Migrations
python manage.py makemigrations
python manage.py migrate

# update seTtings
Adding Order and Customer classes
