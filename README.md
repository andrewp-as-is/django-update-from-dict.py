<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-update-from-dict.svg?maxAge=3600)](https://pypi.org/project/django-update-from-dict/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-update-from-dict.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-update-from-dict.py/actions)

### Installation
```bash
$ [sudo] pip install django-update-from-dict
```

#### Examples
Mixin:
```python
from django.db import models
from django_update_from_dict import update_from_dict, UpdateFromDictMixin

class ClassName(UpdateFromDictMixin,models.Model):
    ...

instance = ClassName()
instance.update_from_dict(attrs,commit=True)
```

function:
```python
from django_update_from_dict import update_from_dict

update_from_dict(instance,attrs,commit=True)
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
