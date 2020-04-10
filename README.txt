Steps to making model changes:
1. Change your models (in models.py).
2. Run python manage.py makemigrations to create migrations for those changes
3. Run python manage.py migrate to apply those changes to the database.

Create a cuperuser:
1. python manage.py createsuperuser

Start the server
1. python manage.py runserver

Run app test cases
1. python manage.py test polls

Use management shell
1. python manage.py shell

Find django source codes
1. python -c "import django; print(django.__path__)"