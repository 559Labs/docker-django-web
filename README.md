# 559labs/django-web

This image defines a basic Django 1.10 setup with a few packages pre-installed
that I generally use.

## Database Selection
Once the image is up and running, you can change the project/settings.py to reference
the postgres configuration. By default, it allocates sqlite3 to avoid any dependency
issues.

## Port Selection
By default, this image attaches to port 8000. Using a docker-compose.yml file, you can
map this to whatever you would like.
