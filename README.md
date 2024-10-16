# CODTECH-TASK-1

Name: Sahana M Tandur

Company: CODTECH IT SOLUTIONS

Intern ID: CT12DS2334

Domain: DEVOPS

Duration: September 5th to November 5th

Mentor: SANTOSH NEELA

Project: KUBERNETES FOR CONTAINER ORCHESTRATION 

Technology used: AWS, Python, django





# django-todo
A simple todo app built with django
-------------------------------------
![task2](https://github.com/user-attachments/assets/18fe95d0-c988-4c03-9b32-03a1b72361c7)

### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/Sahanamtandur/django-todo.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.co
m/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)
