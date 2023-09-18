# Poll-app

A basic poll application consisting of two parts:

- A public site that lets people view polls and vote in them.
- An admin site that lets you add, change, and delete polls.

## Quick start

```
# Setup virtual environment
poetry install

# Setup migrations
# python manage.py makemigrations polls
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Run server
python manage.py runserver
```

## Available pages

- http://127.0.0.1:8000/admin/: Admin panel
- http://127.0.0.1:8000/polls/: Polls list
- http://127.0.0.1:8000/polls/<poll_id>/results/: Poll results
- http://127.0.0.1:8000/polls/<poll_id>/vote/: Vote for a poll

