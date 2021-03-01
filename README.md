# flaskapp
A flask web app for blogging purpose with SQLite as a database

# Functionalities for the blogging web app
1. User can register/login
2. CRUD on blogs
3. Password authentication with 3 limits
4. Filter blogs on basis of like/crated
5. Like post if user is authenticated

## Installation guidelines

- Create virtual environment
```
python -m venv /path/to/new/virtual/environment
```

- Use pip package manager for installation of dependencies
```
pip install Flask
```

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
## Check the output at the below given URL
Link - http://127.0.0.1:5000

## Reference Screenshot

-  Index/Home view 
![Alt text](/images/v4.png)

- If not a use need to register to post - Registration view
![Alt text](/images/v5.png)

- If already a user - Login view 
![Alt text](/images/v6.png)

- User after loggin in 
![Alt text](/images/v1.png)

- New post view for authenticated users
![Alt text](/images/v2.png)

- Update/Delete post view for authenticated users
![Alt text](/images/v3.png)