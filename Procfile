release: python manage.py migrate --noinput
web: gunicorn mysite.wsgi
release: python manage.py makemigrations --noinput
release: python manage.py collectstatic --noinput
