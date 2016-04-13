Strongly recommend to use linux for development

# installation
1. install `python` and `pip` // Установка интерпретатора python и вспомогательного установщика pip
1. run `pip install -r REQUIREMENTS.txt` //  (1)	Задание внешних вспомогательных пакетов для dlango.
1. run `./manage.py sync --all` // and create superuser when suggested (2) Синхронизирование модеи данных в базе, проверка наличия необходимых таблиц)
1. run `./manage.py migrate --fake` //сохранение изменений в моделях)
1. run `./manage.py shell` and type: `import django;django.contrib.sites.models.Site.objects.create(name='example.cdom', domain='example.codm')`  //Запуск интерактивного интепретатора python 

# run development server
To run development server:  `./manage.py runserver`
