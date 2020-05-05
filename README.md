# django-mezzanine-practice
Django CMS by Mezzanine

## Mezzanine intall

[Mezzanine](https://github.com/stephenmcd/mezzanine)

Using Django 2.2 have to follow [this](https://github.com/stephenmcd/mezzanine/issues/1910)

``` bash
pip install git+https://github.com/fermorltd/mezzanine.git@2.2-compat
pip install -U git+https://github.com/fermorltd/filebrowser-safe.git@2.2-compat
pip install -U git+https://github.com/fermorltd/grappelli-safe.git@2.2-compat
python manage.py createdb
python manage.py runserver
```

## Mezznani themes

[mezzanine-themes](https://github.com/thecodinghouse/mezzanine-themes)

Using themes in `settings.py` INSTALLED_APPS
- nova
- moderna
- flat
- solid
