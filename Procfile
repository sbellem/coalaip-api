web: gunicorn config.wsgi:application
worker: celery worker --app=coalaipapi.taskapp --loglevel=info
