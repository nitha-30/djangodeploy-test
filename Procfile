web: gunicorn sampleHeroku.wsgi:application --log-file -
heroku ps:scale web=1
python3 manage.py migrate