web: gunicorn auctionsbyangelu.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
web: python manage.py runserver 0.0.0.0:$PORT 
