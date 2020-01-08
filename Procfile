web: gunicorn workoutApp.wsgi --log-file -
release: python manage.py makemigrations restaurant && python manage.py migrate
