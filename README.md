# React with Django 
Step 1: 

django-admin startproject ReactwithDjango 

django-admin startapp frontend 

Add frontend app to Setting.py 

Go to urls.py in ReactWithDjango 
"from django.urls import path, include" in Line 17 

"path('', include('frontend.urls'))"  in line 22


Create urls.py in frontend

Create a folder in fronend - templates 
Inside templates create a folder frontend 
Inside templates/frontend create index.html

Copy Paste the code from the Hyperlinked index.html 

Create a folder 'static' in frontend and then inside static create 3 folders - css, frontend, images

Inside css create a file index.css 







