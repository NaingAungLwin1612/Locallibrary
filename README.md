# djangoApp-MDN-

## Create virtual environment

`python -m venv .venv`

## Activate virtual environment

`.venv\Scripts\activate`

## Install dependencies

`python -m pip install -r requirements.txt`

## Create MySQL database

create mysql database name with `locallibrary`

name = locallibrary

port = 3306

host = localhost

username = root

password = root

*** if your database config not satify with above, you can fix mysql database setting in my.cnf file. ***

## Migrate database

`python manage.py makemigrations`

`python manage.py migrate`

## Create admin

`python manage.py createsuperuser`

*** Add user name, email and password. ***

## Run app

`py manage.py runserver`

### Admin pannel

[/admin/](http://localhost:8000/admin/)

### Local library app

[/catalog/](http://localhost:8000/polls/)

## Testing

`py manage.py test polls`
