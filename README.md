# django-poll-app
Basic poll application. The app consists of:
- a public site that lets people view questions and vote
- an admin site that lets admins create questions and potential answers

## Prerequisites
Create a virtual environment using Python 3

```console 
$ python3 -m venv env
``` 

Activate your virtual environment
```console
$ source env/bin/activate
```

Change into the outer **mysite** directory and install packages in the requirements.txt file

```console
$ pip install -r requirements
```

## Start the development server
Run this command in your terminal
```console
$ python manage.py runserver
```
Click the link that appears, and add the admin/ or polls/ URL patterns to land on the admin or public site.
## Author
Yemi Ogoundele, yemi.ogoundele@hotmail.fr

