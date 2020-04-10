Steps to making model changes:
1. Change your models (in models.py).
2. Run python manage.py makemigrations to create migrations for those changes
3. Run python manage.py migrate to apply those changes to the database.

Create a cuperuser:
1. python manage.py createsuperuser

Start the server
1. python manage.py runserver
