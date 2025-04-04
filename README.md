# Todo-Django-cicd
This repository demonstrates the deployment of a live DevOps project using a Jenkins CI/CD pipeline with GitHub integration. It automates build, test, and deployment processes, ensuring seamless and efficient software delivery.


# Django Todo App
A simple to-do application built using Django.

![Todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)

## Getting Started
To set up this project locally, follow these steps:

### Clone the Repository
Ensure you have Git installed, then run:
```bash
$ git clone https://github.com/shreys7/django-todo.git
```

### Install Django
Django must be installed on your system to run this app. Follow the installation guide at [Django's official site](https://www.djangoproject.com/download/).

### Apply Database Migrations
Navigate to the cloned project directory and run:
```bash
$ python manage.py makemigrations
$ python manage.py migrate
```
These commands will set up the necessary database migrations.

### Create a Superuser
To access the admin panel, create a superuser by executing:
```bash
$ python manage.py createsuperuser
```
Follow the prompts to set up a username, password, and email.

### Run the Development Server
Start the Django server with:
```bash
$ python manage.py runserver
```
Once the server is running, open your browser and go to:
[http://127.0.0.1:8000/todos](http://127.0.0.1:8000/todos)

to start using the To-Do App.

---

Enjoy coding and managing your tasks efficiently! 🚀

