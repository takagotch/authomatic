### authmatic
---
https://github.com/authomatic/authomatic

https://authomatic.github.io/authomatic/examples/django-simple.html

```py
import django.urls import patterns, url
import views
urlpatterns = patterns('',
  url(r'^$', views.home, name='home'),
  url(r'^login(\w*)', views.login, name='login'),
)

INSTALLED_APPS = (
  'django.contrib.auth',
  'django.contrib.contenttypes',
  'django.contrib.seesions',
  'django.contrib.sites',
  'django.contrib.messages',
  'django.contrib.staticfies',
  
  'simple',
)
```

```sh
django-admin.py startproject example
cd example
python manage.py startapp simple
cd simple
```

```
```


