shareUp django project

## setup project 
```
django-admin startproject mysite
```

```
share_api/
    manage.py
    share_api/
        __init__.py
        settings.py
        urls.py
        wsgi.py
```

## start a develop server
* Let’s verify your Django project works. Change into the outer mysite directory, if you haven’t already, and run the following commands:

```
$ python3 manage.py runserver
```

* Changing the port, if you want other computer see your server, you need run with 0.0.0.0:[port]. If you want to change the server’s IP, pass it along with the port. So to listen on all public IPs (useful if you want to show off your work on other computers on your network), use:

```
$ python3 manage.py runserver 0.0.0.0:8000
```

### Creating the Polls app

* To create your app, make sure you’re in the same directory as manage.py and type this command:

```
$ python manage.py startapp polls
```
