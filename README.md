# Kittygramm

https://github.com/sined2904/kittygram_final/actions/workflows/main.yml/badge.svg

### Описание
Социальная сеть для котиков. Каждый может показать своего котика и посмотреть на других

### Технологии
Django==3.2.3
djangorestframework==3.12.4
djoser==2.1.0
webcolors==1.11.1
psycopg2-binary==2.9.3
Pillow==9.0.0
pytest==6.2.4
pytest-django==4.4.0
pytest-pythonpath==0.7.3
PyYAML==6.0
gunicorn==20.1.0

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