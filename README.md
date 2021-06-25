# JWT Token Authentication

Using JWT authentication with Django Rest Framework.


## API endpoints:

* `/api/user/register/`
* `/api/user/login/`
* `/api/user/`
* `/api/user/logout/`


## Example usage

This repo can be used from the command line with the following steps:

```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

```

You can also use it with **httpie** as follows:

```
http GET http://127.0.0.1:8000/api/user/ "Cookie:access_token=<the access token>"
```
