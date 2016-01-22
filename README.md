<<<<<<< HEAD
# php-getting-started

A barebones PHP app that makes use of the [Silex](http://silex.sensiolabs.org/) web framework, which can easily be deployed to Heroku.

This application supports the [Getting Started with PHP on Heroku](https://devcenter.heroku.com/articles/getting-started-with-php) article - check it out.

## Deploying

Install the [Heroku Toolbelt](https://toolbelt.heroku.com/).

```sh
$ git clone git@github.com:heroku/php-getting-started.git # or clone your own fork
$ cd php-getting-started
$ heroku create
$ git push heroku master
$ heroku open
```

## Documentation

For more information about using PHP on Heroku, see these Dev Center articles:

- [PHP on Heroku](https://devcenter.heroku.com/categories/php)
=======
# python-getting-started

A barebones Python app, which can easily be deployed to Heroku.

This application support the [Getting Started with Python on Heroku](https://devcenter.heroku.com/articles/getting-started-with-python) article - check it out.

## Running Locally

Make sure you have Python [installed properly](http://install.python-guide.org).  Also, install the [Heroku Toolbelt](https://toolbelt.heroku.com/) and [Postgres](https://devcenter.heroku.com/articles/heroku-postgresql#local-setup).

```sh
$ git clone git@github.com:heroku/python-getting-started.git
$ cd python-getting-started
$ pip install -r requirements.txt
$ createdb python_getting_started
$ heroku local:run python manage.py migrate
$ python manage.py collectstatic
$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master
$ heroku run python manage.py migrate
$ heroku open
```
or

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Python on Heroku, see these Dev Center articles:

- [Python on Heroku](https://devcenter.heroku.com/categories/python)
# Hello 
>>>>>>> ccccd9a7a19938b965177a81caa173bbcc07d2fa
# blog1
# blog1
# blog1
