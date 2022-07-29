release: python manage.py managemigrations --no-input
release: python manage.py migrate --no-input


web: gunicorn contactsapi.wsgi