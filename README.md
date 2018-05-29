# MyEcommerce
My e-ecommerce: Django 2.x - Python 3.x

# CLI
python -m venv myenvironment
cd myenvironment
Scripts\activate || deactivate

pip3 install django
python

import django
django.get_version()
django.VERSION
exit()

# Create new project
pwd
source bin/activate

django-admin startproject chipchip
python manage.py migrate
python manage.py runserver

# The shop app
python manage.py startapp shop

# Make models to DB
python manage.py makemigrations
python manage.py migrate

# Craete Super User
python manage.py createsuperuser
name: chipchip
pass: chip2409

# Django Shell
python manage.py shell

# Command Templates

Block tags are represented like this.

{% block any...name %}
  you put the code here...
{% endblock %}
 
{% comment %}
  you put the code here...
{% endcomment %}
 
{% for... %}
  you put the code here...
{% endfor %}
 
 There are some exceptions like
 
{% url '...' %}
{% load ... %}
{% extends "base.html" %}
