## Django

---
1. mkdir
2. poetry init -n
3. poetry add django
4. poetry add --dev black flake8 django-cors-headers
5. poetry shell
6. django-admin startproject things .
7. python things/manage.py runserver
8. python things/manage.py migrate
9. python things/manage.py createsuperuser
10. python things/manage.py startapp home
11. provide corsheader and Your app name and add it to 
    INSTALLED_APPS in setting file
12. python things/manage.py makemigrations
13. python things/manage.py migrate
14. to test = python things/manage.py test
