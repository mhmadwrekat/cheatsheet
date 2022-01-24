## Gunicorn & Whitenoise

---

1. poetry add gunicorn whitenoise
2. poetry export -f requirements.txt > requirements.txt --without-hashes
3. in docker-compooese 
	-> command: gunicorn things.wsgi:application --bind 0.0.0.0:8000 --workers 4
4. In Setting :
   - add to MIDDLEWERE -> 'whitenoise.middleware.WhiteNoiseMiddleware',
   - 	STATIC_ROOT = BASE_DIR / 'staticfiles'
		STATICFILES_DIRS = [
    			BASE_DIR / 'static' ]
5. docker-compose run web python manage.py migrate
6. docker-compose run web python manage.py createsuperuser
