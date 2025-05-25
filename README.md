# Django Starter Template

A minimal Django boilerplate for starting new web development projects.

## Features

- Django
- Environment variables with `python-decouple`
- Static + Template folder
- GitHub-ready

## Setup

```bash
git clone https://github.com/yourusername/django-starter.git
cd django-starter
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env  # or create your own
python manage.py migrate
python manage.py runserver

### Tailwindcss

This project uses Tailwindcss via PostCSS and Tailwind CLI

To Build the css:

```bash
npm install
npm run dev
