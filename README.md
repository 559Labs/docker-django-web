# 559labs/django-web

This image defines a basic Django 1.10 setup with a few packages pre-installed
that I generally use:

- Django 1.10
- django-bootstrap3 7.0.1
- django-extensions 1.7.1
- django-grappelli 2.8.1
- docopt 0.6.2
- jedi 0.9.0
- Pillow 3.3.0
- prompt-toolkit 1.0.5
- psycopg2 2.6.2
- ptpython 0.35
- Pygments 2.1.3
- six 1.10.0
- wcwidth 0.1.7
- Werkzeug 0.11.10

## Database Selection
Once the image is up and running, you can change the project/settings.py to reference
the postgres configuration. By default, it allocates sqlite3 to avoid any dependency
issues.

## Port Selection
By default, this image attaches to port 8000. Using a docker-compose.yml file, you can
map this to whatever you would like.
