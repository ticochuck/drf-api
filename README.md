# Django REST Framework

[Link to latest PR](https://github.com/ticochuck/drf-api/pull/1)

## Description

Django REST Framework to create an API, then “containerize” it with Docker.


## Usage

- `poetry shell` to start your virtual environment
- `poetry install` to install dependencies
- create .env file with the following variables and save it into 'snacks_project' directory
    - SECRET_KEY=secret key for the app (typically 50-characters long string)
    - DEBUG=should be set to True in development
    - ALLOWED_HOSTS=localhost,127.0.0.1 (for testing)
- `python manage.py makemigrations` - to generate DB schema
- `python manage.py migrate` - to create DB schema
- `python manage.py createsuperuser` - to create user with admin access
- `python manage.py collectstatic` - to collect apps static files
- `python manage.py runserver` - to run server
- `docker-compose up` - to run with Docker


## Lab31 - Django REST Framework

[Canvas Assignment](https://canvas.instructure.com/courses/2045906/assignments/15160049)

## Author

[Chuck Li Villalobos](https://github.com/ticochuck)


