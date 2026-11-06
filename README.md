# My Django Project (Tennis Club)

A starter Django project (`my_tennis_club`) created while learning the framework. It covers project setup, settings, URL routing and the built-in SQLite database.

## Status

Early-stage learning project. It currently contains the generated project scaffold, configuration and a SQLite database. The `members` app from the tutorial is not yet uploaded to this repository (the folder is an empty reference). Planned next steps:

- [ ] Add the `members` app with a Member model
- [ ] Add views and templates to list and view members
- [ ] Add Django admin configuration and migrations

## Getting started

Prerequisites: Python 3.10+.

```bash
git clone https://github.com/Tshepo1000/mydjangoproject.git
cd mydjangoproject

python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install django

python manage.py migrate
python manage.py runserver
```

Then open http://127.0.0.1:8000/ in your browser.

## Project structure

```
mydjangoproject/
├── manage.py
├── db.sqlite3
└── my_tennis_club/   # settings, urls, wsgi and asgi
```

## Tech stack

Python, Django, SQLite.

## Author

Tshepo Sekete, [GitHub](https://github.com/Tshepo1000)
