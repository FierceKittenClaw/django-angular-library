# Django Angular Library

### Requirements
[Django](https://www.djangoproject.com/) 1.3 or later

### Installation

```
$ pip install django-angular-library
```

### Setup

Just add ```'django.contrib.staticfiles'``` and ```'angular'``` to
INSTALLED_APPS in yoursettings.py

```
INSTALLED_APPS = (
    # ...

    'django.contrib.staticfiles',
    'angular',

    # ...
)
```

Refer to Django [static files](https://docs.djangoproject.com/en/dev/howto/static-files/)
documentation to configure and deploy static files.

### Usage

You can refer to angular in your template with:

```
{{ STATIC_URL }}js/angular.js
```