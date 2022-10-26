Simple Flask Todo App using SQLAlchemy and SQLite database.

For styling [semantic-ui](https://semantic-ui.com/) is used.

### Setup
Create project with virtual environment

```console
$ mkdir myproject
$ cd myproject
$ python3 -m venv venv
```

Activate it
```console
$ . venv/bin/activate
```

or on Windows
```console
venv\Scripts\activate
```

Install requirements
```console
$ pip install -r requirements.txt
```

Set environment variables in terminal
```console
$ export FLASK_APP=app.py
$ export FLASK_ENV=development
$ export SIDEKICK_APIKEY=<YOUR-SIDEKICK-API-KEY>
$ export SIDEKICK_APPLICATION_NAME=flask-todo
$ export SIDEKICK_APPLICATION_STAGE=dev
$ export SIDEKICK_APPLICATION_VERSION=1.0
```

or on Windows
```console
$ set FLASK_APP=app.py
$ set FLASK_ENV=development
$ set SIDEKICK_APIKEY=<YOUR-SIDEKICK-API-KEY>
$ set SIDEKICK_APPLICATION_NAME=flask-todo
$ set SIDEKICK_APPLICATION_STAGE=dev
$ set SIDEKICK_APPLICATION_VERSION=1.0
```

Run the app
```console
$ flask run
```
