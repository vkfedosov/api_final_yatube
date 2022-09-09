# Проект API для Yatube

## Описание проекта:
Yatube API для проекта социальной сети Yatube

## Стек технологий:
* [Python 3.7](https://www.python.org/downloads/)
* [Django 2.2.16](https://www.djangoproject.com/download/)
* [Django Rest Framework 3.12.4](https://pypi.org/project/djangorestframework/#files)
* [Pytest 6.2.4](https://pypi.org/project/pytest/)
* [Simple-JWT 1.7.2](https://pypi.org/project/djangorestframework-simplejwt/)

## Как запустить проект:

* Клонировать репозиторий и перейти в него в командной строке
```
git clone git@github.com:vkfedosov/api_final_yatube.git
```
```
cd api_final_yatube
```

* Cоздать и активировать виртуальное окружение:
```
python -m venv env
```
```
venv/scripts/activate
```

* Установить зависимости из файла ```requirements.txt```:
```
pip install -r requirements.txt
```

* Выполнить миграции:
```
python manage.py migrate
```

* Запустить проект:
```
python manage.py runserver
```

## Документация к проекту:
```
Документация для Yatube API доступна по адресу /redoc/.
```