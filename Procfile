web: gunicorn workoutApp.wsgi --log-file -
release: python manage.py makemigrations food && python manage.py migrate
