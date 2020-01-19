# How to run this app

## Prerequites

Postgresql 10.3

pipenv 2018.11.26

Created on OSX Catalina, not tested on any other system.

```bash
pipenv install --dev
```

```bash
createdb cr-test
```

```bash
python manage.py loaddata dummy_data.json
```
