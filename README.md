This is a template project just used for restful api development


### Project Structure

```
src/
├── requirements.txt
├── README.md
├── MANIFEST.in
├── LICENSE
├── .gitignore
└── project_name
    ├── __init__.py
    ├── wsgi.py
    ├── requirements.txt
    ├── manage.py
    ├── fabfile.py
    ├── app
    │   ├── __init__.py
    │   ├── api
    │   │   └── __init__.py
    │   ├── controllers
    │   │   └── __init__.py
    │   ├── models
    │   │   ├── model_a
    │   │   │   ├── __init__.py
    │   │   │   ├── models.py
    │   │   │   ├── parameters.py
    │   │   │   ├── resources.py
    │   │   │   └── schemas.py
    │   │   └── model_b
    │   │       ├── __init__.py
    │   │       ├── models.py
    │   │       ├── parameters.py
    │   │       ├── resources.py
    │   │       └── schemas.py
    │   ├── static
    │   └── utils
    │       └── __init__.py
    ├── config
    │   ├── __init__.py
    │   ├── default.py
    │   ├── development_sample.py
    │   ├── production_sample.py
    │   └── testing.py
    ├── db
    │   └── db_files
    └── deploy
        ├── flask_env.sh
        ├── gunicorn.conf
        ├── nginx.conf
        └── supervisor.conf
```