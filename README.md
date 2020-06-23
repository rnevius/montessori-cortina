# Centro Montessori Cortina

Django + Wagtail site for Centro Montessori Cortina in Cortina d'Ampezzo, Italy.

## Development

1. Install Python 3 and [Poetry](https://python-poetry.org/docs/).
2. Install dependencies:

        poetry install

3. Grab a copy of the test database. The development superuser is `admin / adminadminadmin`.
4. Run migrations:

        poetry run python manage.py migrate

5. Run the server:

        poetry run python manage.py runserver

### QA Considerations

1. Run the Black formatter before committing:

        poetry run black --include **/*.py --target-version py38
