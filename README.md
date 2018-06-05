# Car Rental

**Getting Started**

A car rental system. Written in Django.

**Installation**

clone repo

	
	git clone https://github.com/frknnlzts/CarRental.git
	

go into repo

	
	cd carrental
	

make a virtual environment

	
	virtualenv env (pip install virtualenv)
	python3 –m venv carenv
	

start the env

	
	source carenv/bin/activate
	

install the requirements
	
	
	pip install -r requirements.txt
	

Now run the database migrations

	
	python manage.py migrate
	

Now run the server

	
	python manage.py runserver
	

Head to `http://127.0.0.1:8000/`


**Admin Site**

Create superuser for admin site

	
	python manage.py createsuperuser
	
	
Head to `http://127.0.0.1:8000/admin`
