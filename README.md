# Little Lemon Back-end Capstone

A simple Django REST Framework project for the Little Lemon restaurant.

## Features
- Django web application with static HTML
- MySQL database configuration
- Menu API
- Table booking API
- User registration and token authentication
- Unit tests
- REST API suitable for Insomnia testing

## Setup
1. Create and activate a virtual environment.
2. Run `pip install -r requirements.txt`.
3. Create a MySQL database named `littlelemon`.
4. Update database credentials in `littlelemon/settings.py`.
5. Run `python manage.py makemigrations`.
6. Run `python manage.py migrate`.
7. Run `python manage.py createsuperuser`.
8. Run `python manage.py runserver`.

## API paths
GET/POST: `/restaurant/menu/`
GET/PUT/DELETE: `/restaurant/menu/<id>/`

GET/POST: `/restaurant/booking/`
GET/PUT/DELETE: `/restaurant/booking/<id>/`

Registration: `/auth/users/`
Token login: `/auth/token/login/`

## Note
The project is configured for MySQL. Update the username, password and host in settings.py before running it.
