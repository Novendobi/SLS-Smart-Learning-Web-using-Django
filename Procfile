#web: gunicorn smartlearning.wsgi:application --log-file - --log-level debug

web: python3 manage.py migrate; python3 manage.py collectstatic --no-input; python3 manage.py; gunicorn smartlearning.wsgi --bind 0.0.0.0:8000