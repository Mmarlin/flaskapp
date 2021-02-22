# flaskapp

## Running guidlines

-  Export env and app name, make sure to be in the root directory, i.e flaskapp

```
set FLASK_APP=flaskr

set FLASK_ENV=development

flask run
```

## Initialize DB

- We've added a flask management command utility with click
```
flask init-db
```

- Check all available management commands
```
flask --help
```
