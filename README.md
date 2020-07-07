Flask Sample App

First Steps
$ pyvenv-3.5 env
$ source env/bin/activate
$ pip install -r requirements.txt
Set up Migrations
$ python manage.py db init
$ python manage.py db migrate
$ python manage.py db upgrade
Run
Run each in a different terminal window...

# redis
$ redis server

# worker process
$ python worker.py

# the app
$ python app.py
