# Env & Deploy

---
## Env
- poetry add django-environ
- add it to git ignore

---
## Deploy

- heroku apps:create name
- git remote -v
- heroku git:remote -a name
- heroku stack:set container
- git add .
- git commit -m'message'
- git push heroku main
