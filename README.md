Step 1: 

django-admin startproject ReactwithDjango 

django-admin startapp frontend 

Add frontend app to Setting.py 

Go to urls.py in ReactWithDjango 
"from django.urls import path, include" in Line 17 

"path('', include('frontend.urls'))"  in line 22



