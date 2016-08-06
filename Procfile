web: newrelic-admin run-program gunicorn --pythonpath="$PWD/myapis" wsgi:application
worker: python myapis/manage.py rqworker default