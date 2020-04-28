# Django-backend-api

With docker installed and running
~~~
docker-compose build .
docker-compose run --rm app sh -c "python manage.py test && flake8"
docker-compose run --rm app sh -c "python manage.py migrate"
docker-compose run --rm app sh -c "python manage.py runserver"
~~~