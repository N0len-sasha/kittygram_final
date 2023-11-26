[![Main Kittygram workflow](https://github.com/N0len-sasha/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/N0len-sasha/kittygram_final/actions/workflows/main.yml)

# Описание 
Проект Kittygram представляет собой сайте, для обмена карточками котов. 
На сайте есть авторизация и регистрация. Для авторизированных пользователей 
доступно создание своих котов с различными параметрами и фото. 
# Технологический стек проекта 
`Python` `DJANGO` `Nginx` `Docker-compose` `JavaScript` `React` 
 
# Установка 
## Как развернуть проект на локальной машине 
### Клонировать репозиторий и перейти в него в командной строке 
``` 
  git clone https://github.com/N0len-sasha/kittygram_finae.git 
``` 
``` 
  cd kittygram_fina 
``` 
### Создать и активировать виртуальное окружение 
``` 
  python -m venv venv 
``` 
``` 
  source venv/Scripts\activate 
``` 
### Установить зависимости 
``` 
cd backend 
``` 
``` 
  pip install -r requirements.txt 
``` 
### Выполнить миграции 
``` 
  python manage.py migrate 
``` 
### Запустить проект 
``` 
  python manage.py runserver 
``` 
## Создать файл .env 
### Создать файл с названием .env в корне проекта 
### Добавить в него слудующее 
``` 
SECRET_KEY=project_secre_key 
DEBUG=True 
POSTGRES_DB=kittygram 
POSTGRES_USER=kittygram_user 
POSTGRES_PASSWORD=kittygram_password 
DB_NAME=kittygram 
DB_HOST=db 
DB_PORT=5432 
``` 
 
## Автор 
Платошин Александр Игоревич 

