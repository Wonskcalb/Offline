# Offline
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/ecb6f5188ca94ed4a6bd8224c251550e)](https://www.codacy.com/manual/Wonskcalb/Offline?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Wonskcalb/Offline&amp;utm_campaign=Badge_Grade)

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
