Шаблон основан на статье https://gracious-grace.hashnode.dev/how-to-deploy-a-django-app-to-heroku


heroku login
heroku create my-app
git push heroku main

heroku run python manage.py migrate
heroku run python manage.py createsuperuser