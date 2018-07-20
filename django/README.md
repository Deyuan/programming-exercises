## programming-exercises/django

## Exercises
* [mysite](mysite) - Django tutorial: A poll application
  * `python -m django --version`
  * `django-admin startproject mysite`
  * `python manage.py startapp polls`
  * `python manage.py runserver`
  * `python manage.py migrate`
  * `python manage.py makemigrations polls`
  * `python manage.py sqlmigrate polls 0001`
  * `python manage.py shell`
  * `python manage.py createsuperuser`
  * `python manage.py test polls`
  * `python -c "import django; print(django.__path__)"`
* [django-polls](django-polls) - Django tutorial: Packaging the app
  * `python setup.py sdist`
  * `pip install --user django-polls/dist/django-polls-0.1.tar.gz`
  * `pip uninstall django-polls`

## References
* Django Tutorial
  * https://docs.djangoproject.com/en/2.0/intro/
  * https://www.djangoproject.com
* Django Wikipedia
  * https://en.wikipedia.org/wiki/Django_(web_framework)
* Django Github Repo
  * https://github.com/django/django
* Django Documentation
  * http://devdocs.io/django~2.0/
  
