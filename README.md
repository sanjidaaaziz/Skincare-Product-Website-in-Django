# Skincare-Product-Website-in-Django
The online shopping project with Django is a reliable e-commerce application that enables users to browse and purchase products online securely. The system provides users with an easy-to-use interface, secure payment processing, and robust database management.

## Steps to run the system
These are the step’s to run an Online Skincare Product Website Project in Django:
1.	pip install virtualenv
Firstly, we need to install the virtualenv, Open a command prompt by going to the project folder directory and typing CMD. After opening the CMD type “ pip install virtualenv”.
2.	virtualenv env
Then, after installing virtualenv we have to type “virtualenv env” and enter.
3.	cd env/Scripts
Next, we must type. “cd env/Scripts” and press enter.
4.	Activate
Next, we need to type “activate” then press enter.
5.	cd ../..
Then will type “cd ../..” and press enter.
6.	Install Django
To install Django, “pip install django” command is need to be typed.
7.	python manage.py makemigrations
After installation of  the requirements, we need to type this command “python manage.py makemigrations” to create a tables in the database.
8.	python manage.py migrate –run-syncdb
The command “python manage.py migrate –run-syncdb” need to be typed after making migrations to migrate the tables in database.
9.	python manage.py createsuperuser
After migration of database you need to create super user to login in the admin account, just you need is to type the command “python manage.py createsuperuser”.
10.	python manage.py runserver
Lastly, after creating super user, the command “python manage.py runserver” need to be typed for testing and launching the project.
11.	http://127.0.0.1:8000/
Finally, to access the project dashboard, we have to copy this URL “http://127.0.0.1:8000/” into our browser.
