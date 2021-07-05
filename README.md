# heroku-django-api-template

## Local deployment:
1. Migrate with ``python manage.py makemigrations`` and ``python manage.py migrate``.
2. Create super user for admin-page access with ``python manage.py createsuperuser``.
3. Start development server with ``python manage.py runserver --settings=apiserver.local_settings``.
4. ``ExampleEntity`` has been added as an example for a fast start. Edit it to fit your needs.