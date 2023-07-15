# Kittygramm

![](https://github.com/sined2904/kittygram_final/actions/workflows/main.yml/badge.svg)

### Описание
Социальная сеть для котиков. Каждый может показать своего котика и посмотреть на других

### Технологии
Django
djangorestframework
djoser
webcolors
psycopg2-binary
Pillow
pytest
pytest-django
pytest-pythonpath
PyYAML
gunicorn

### Запуск проекта в dev-режиме
- Установите и активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
``` 
- Заполните файл .env
- В корневой папке проекта выполните команду:
```
docker compose up 
```

### Описание переменных окружения
POSTGRES_DB - название БД
POSTGRES_USER - имя пользователя БД
POSTGRES_PASSWORD - пароль пользователя БД
DB_NAME - название БД
DB_HOST - адрес БД
DB_PORT - порт БД
SECRET_KEY - криптографическая подпись Django
DEBUG - статус режима дебаг

### Авторы
Пиневич Денис

Github - Sined2904
Den2904@yandex.ru
TG - @PinevichD