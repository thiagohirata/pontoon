web: gunicorn pontoon.wsgi:application --log-file -
worker: celery worker --app=pontoon.base.celeryapp --loglevel=info --without-gossip --without-mingle --without-heartbeat
