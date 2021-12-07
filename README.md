# addictea

## setup your env
```sh
# install dependencies into a virtual environment
$ virtualenv venv
$ pip install -r requirements.txt
$ pip install -r requirements-dev.txt

# run db migrations
$ python manage.py db upgrade

# load db fixtures (optional)
$ python manage.py db fixtures fixtures.json

# start frontend dev server:
$ npm install
$ npm run start

# start backend dev server:
$ python manage.py run

# start backend celery worker (currently only required for sending emails):
$ python manage.py celery worker
```
