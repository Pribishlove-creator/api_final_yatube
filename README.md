# API для Yatube

**_Учебный проект._**

## Описание:
Yatube - социальная сеть для публикации дневников. Позволяет публиковать посты, комментировать посты, добавлять в группу, осуществлять подписку на авторов.
Для аутентификации используется JWT-токен.

## Стек технологий
Python3, Django 3, Django REST Framework, SQLite3, Simple JWT.

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/devlili/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

### Создание суперпользователя
Выполнить команду и следовать инструкциям:
```
python manage.py createsuperuser
```
После создания супепользователя можно использовать данные учетной записи для страницы администрирования - http://127.0.0.1:8000/admin/

## Документация к API

 После запуска dev-сервера документация к API доступна по адресу:
 http://127.0.0.1:8000/redoc/
