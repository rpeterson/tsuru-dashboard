#Abyss (Tsuru Dashboard)

[![Build Status](https://secure.travis-ci.org/tsuru/tsuru-dashboard.png?branch=master)](http://travis-ci.org/tsuru/tsuru-dashboard)
[![Build Status](https://drone.io/github.com/tsuru/tsuru-dashboard/status.png)](https://drone.io/github.com/tsuru/tsuru-dashboard/latest)

Abyss is a django-base project aimed to providing a tsuru dashboard.


For issue tracking:

    * https://github.com/tsuru/tsuru-dashboard/issues

#Getting Started

For local development, first create a virtualenv and install the deps:

    $ make deps

If all is well you should able to run the local server:

    $ export TSURU_HOST=http://tsuru-api-endpoint.com
    $ ./manage.py runserver

#Running tests

    $ make test
