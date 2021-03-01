# flaskapp
A flask web app for blogging purpose with SQLite as a database

# Functionalities for the blogging web app
1. User can register/login
2. CRUD on blogs
3. Password authentication with 3 limits
4. Filter blogs on basis of like/crated
5. Like post if user is authenticated

## Activate Virtual Environment
```
venv_flask\Scripts\activate

cd venv_flask

cd flaskapp
```

## Initialize DB

- Aadded a flask management command utility with click
```
flask init-db
```

- Check all available management commands
```
flask --help
```

## Running guidlines

-  Export env and app name, make sure to be in the root directory, i.e flaskapp

```
set FLASK_APP=flaskr

set FLASK_ENV=development

flask run
```
## Check the output of the at the below given URL
Link - http://127.0.0.1:5000

## Reference Screenshot

