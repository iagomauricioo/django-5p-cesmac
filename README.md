# Django 5º período faculdade

### Criando super usuário

<a href="https://www.digitalocean.com/community/tutorials/how-to-enable-and-connect-the-django-admin-interface">Link explicando</a>

```python 
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'nome-do-modulo-que-você-criou',
]

`python manage.py migrate`


```python 
Output
Operations to perform:
  Apply all migrations: admin, auth, blogsite, contenttypes, sessions
Running migrations:
  No migrations to apply.

```

ip do admin: http://localhost:8000/admin/


`python manage.py createsuperuser`

```python
Output
Username (leave blank to use 'root'): admin_user
Email address: sammy@example.com
```