# Offline
The only usable and open source app to allow time off management.

## Installation
```bash
# Clone project and cd into it.
poetry install
cd src/frontend
npm install
```

## Running the service

```bash
poetry run ./manage.py migrate
poetry run ./manage.py collectstatic  # This will be useful only if DEBUG = False
poetry run ./manage.py runserver
```
