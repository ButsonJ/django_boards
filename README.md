# django_boards

Simple Fourms website, with secure accounts, admin portal and testing.

Project built using Django, HTML, CSS, and bootsrap.

This was ported over from a zip file so I lost the original README. 

First, clone the repository to your local machine:

```bash
git clone git@github.com/com/ButsonJ/django_boards
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Setup the local configurations:

```bash
cp .env.example .env
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.

Youd should be able to run this on windwos as it no longer has Redis caching
