## About

This project was created following the [Django Project tutorial](https://docs.djangoproject.com/en/4.0/intro/tutorial01/).

## Important Workflows

### Starting Development Server
`python manage.py runserver`

### Making Model Changes
1. Change your models (in models.py).
2. Run `python manage.py makemigrations` to create migrations for those changes
3. Run `python manage.py migrate` to apply those changes to the database.
