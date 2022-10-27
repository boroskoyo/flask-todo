<p align="center">
  <img width="60%" height="60%" src="https://4750167.fs1.hubspotusercontent-na1.net/hubfs/4750167/sidekick_v2/sidekick-pycharm.png">
</p>
<p align="center">
    <a href="https://github.com/runsidekick/sidekick" target="_blank"><img src="https://img.shields.io/github/license/runsidekick/sidekick?style=for-the-badge" alt="Sidekick Licence" /></a>&nbsp;
    <a href="https://www.runsidekick.com/discord-invitation?utm_source=sidekick-readme" target="_blank"><img src="https://img.shields.io/discord/958745045308174416?style=for-the-badge&logo=discord&label=DISCORD" alt="Sidekick Discord Channel" /></a>&nbsp;
    <a href="https://www.runforesight.com?utm_source=sidekick-readme" target="_blank"><img src="https://img.shields.io/badge/Monitored%20by-Foresight-%239900F0?style=for-the-badge" alt="Foresight monitoring" /></a>&nbsp;
    <a href="https://app.runsidekick.com/sandbox?utm_source=sidekick-readme" target="_blank"><img src="https://img.shields.io/badge/try%20in-sandbox-brightgreen?style=for-the-badge" alt="Sidekick Sandbox" /></a>&nbsp;
    
</p>

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
$ export SIDEKICK_BROKER_HOST=wss://127.0.0.1 //only if you are running a self hosted version
```

or on Windows
```console
$ set FLASK_APP=app.py
$ set FLASK_ENV=development
$ set SIDEKICK_APIKEY=<YOUR-SIDEKICK-API-KEY>
$ set SIDEKICK_APPLICATION_NAME=flask-todo
$ set SIDEKICK_APPLICATION_STAGE=dev
$ set SIDEKICK_APPLICATION_VERSION=1.0
$ set SIDEKICK_BROKER_HOST=wss://127.0.0.1 //only if you are running a self hosted version
```

Run the app
```console
$ flask run
```
