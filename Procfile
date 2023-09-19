#web: gunicorn smartlearning.wsgi --log-file -
#web: python3 manage.py runserver 0.0.0.0:$PORT

web: python3 manage.py migrate && python3 manage.py collectstatic --no-input && gunicorn smartlearning.wsgi