# djangotest
To setup app:

set `DB_NAME`, `DB_USER`, `DB_PASSWORD`, `DB_HOST` env vars

run `pip install -r requirements.txt`

run `python manage.py migrate`

create user `python manage.py createsuperuser --email test@example.com --username test`

to get organization users
GET `http://127.0.0.1:8000/users/?organization=1`
