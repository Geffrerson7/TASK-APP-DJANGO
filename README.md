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
$ python virtualenv venv
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
    (env)$ python manage.py makemigrations
```

```bash
    (env)$ python manage.py migrate
```

You can now run the development server:

```bash
    (env)$ python manage.py runserver
```

And navigate to

```sh
http://127.0.0.1:8000/
```

## Author

- [Gefferson Max Casasola Huamancusi](https://www.github.com/Geffrerson7)
