# Docker

---
- outside .env
1. new file -> Dockerfile
2. open file and copy and paste
3. new file -> docker-compose.yml
4. open file and copy and paste
5. poetry export -f requirements.txt -o requirements.txt --without-hashes
6. to run first time -> in setting.py
	ALLOWED_HOSTS = ['127.0.0.1', '0.0.0.0']
   ->	docker-compose up --build
7. run -> docker-compose up -d
8. shutdown -> docker-compose down
9. docker-compose run web python manage.py migrate



