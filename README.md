# Bot Template
🇬🇧 Template for a telegrambot powered as django app.

In a proper installed environment this template can be used to create and bootstrap a bot. It provides some often used models, views for help or info pages.
With Django3+ you can direclty install from online zip file like:
```bash
python manage.py startapp --template=https://github.com/telebotter/bottemplate/archive/master.zip <app_name>
```
For older Versions clone the repo or extract the zip file and use it like:
```bash
python manage.py startapp --template=extracted/folder/bottemplate <app_name>
```
Further reading on app templates:
https://docs.djangoproject.com/en/3.0/ref/django-admin/#startapp
https://docs.djangoproject.com/en/3.0/ref/templates/api/#django.template.Context

Add the bot token to DJANGO_TELEGRAMBOT in the settings.py of your project and the bot is ready.
