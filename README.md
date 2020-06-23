# Centro Montessori Cortina

Django + Wagtail site for Centro Montessori Cortina in Cortina d'Ampezzo, Italy.

## Development

1. Install Python 3 and [Poetry](https://python-poetry.org/docs/).
2. Install dependencies:

        poetry install

3. Grab a copy of the test database and test user credentials.
4. Run migrations:

        poetry run python manage.py migrate

5. Run the server:

        poetry run python manage.py runserver
