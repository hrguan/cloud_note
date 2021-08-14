# Cloud Note

## Features
* Users can login and logout.
* Users are able to create, update, delete and view their notes.

## Run Locally
1. Set up  mySQL 
```
$ /usr/local/mysql/bin/mysql -u root -p
$ create database note
```
2. migrate model to database
```
$python3 manage.py makemigrations
＄python3 manage.py migrate
```
3. python3 manage.py runserver
