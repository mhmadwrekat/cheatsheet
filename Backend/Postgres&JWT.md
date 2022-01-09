# Postgres & JWT

---
## Postgres DB

1. poetry add psycopg2-binary
2. poetry export -o requirements.txt --without-hashes
3. docker-compose up -d
4. docker-compose run web python manage.py migrate
5. docker-compose run web python manage.py createsuperuser

---
## JWT

1. poetry add djangorestframework-simplejwt
2. poetry export -f requirements.txt > requirements.txt --without-hashes
3. copy and paste in setting
