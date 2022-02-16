# Django Skeleton

**What does this skeleton include?**
- Custom authentication with username/email login capablities
- Service Worker using updated version of django-pwa to work with django version 4.0
- Javascript file named base.js with function for cookie creation (Useful for ajax requests).
- 3rd party links and minified files such as 
    - anime.js v3.2.1
    - jQuery v3.6.0
    - fontawesome
    - bootstrap
- .env file with variables set for sendgrid, stripe and more...
- Necessary files for Heroku (e.g. runtime.txt, Procfile, Pipfile.lock, etc.)
- A default image in static/images
- CSS file structure (e.g. base, components, themes, etc.)

---
**Clone Repository**
```
git clone https://github.com/shaun-ps-04/django-skeleton.git .
```

Remember to uncomment `config/.env` in `.gitignore`

---
**Include e-mails and payments**
```
pipenv install sendgrid stripe
```

---
Runserver shortcut (runs on port 9000):
```
./server.sh
```

---
**Watch Sass**
In a separate terminal
```
cd static/css
sass --watch main.sass main.css
```