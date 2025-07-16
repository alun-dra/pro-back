web: python manage.py collectstatic --noinput && python manage.py shell -c "from core.initial_superuser import create_superuser; create_superuser()" && gunicorn core.wsgi
