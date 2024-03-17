# TODO-APP-DJANGO

## Description

App made with django and python to create tasks, mark tasks as done and delete tasks

## Getting Started

First clone the repository from Github and switch to the new directory:

```bash
    git clone https://github.com/Geffrerson7/TODO-APP-DJANGO.git
```

```bash
    cd TODO-APP-DJANGO
```

Activate the virtualenv for your project.

```sh
$ virtualenv venv
# windows
$ source venv/Scripts/activate
# Linux
$ source venv/bin/activate
```

Install project dependencies:

```bash
    (env)$ pip install -r requirements.txt
```

Then simply apply the migrations:

```bash
    (venv)$ python manage.py makemigrations taskapp
```

```bash
    (venv)$ python manage.py migrate
```

You can now run the development server:

```bash
    (env)$ python manage.py runserver
```

And navigate to

```sh
http://127.0.0.1:8000/
```

## Local Installation with Docker

Clone the respository

```bash
$ git clone https://github.com/Geffrerson7/TASK-API.git
```

Navigate to the new directory

```bash
$ cd TASK-API
```

Use Docker Compose to build and start the project:
```sh
$ docker-compose up
```

Once the project is up and running, apply migrations to set up the database:
```sh
$ docker-compose exec web python manage.py migrate
```

After applying migrations, navigate to the following URL in your web browser:
```sh
http://127.0.0.1:8000/
```

## Author

- [Gefferson Max Casasola Huamancusi](https://www.github.com/Geffrerson7)
