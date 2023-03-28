# api_final
api final

Описание

API для Yatub представляет собой проект социальной сети в которой реализованы следующие возможности: публиковать записи, комментировать записи, а так же подписываться или отписываться от авторов.

Стек технологий:

Python 3.11,
Django 4.2,
DRF,
JWT + Djoser

Как запустить проект:

Клонировать репозиторий:

git clone https://github.com/lerapraga/api_final_yatube

Cоздать и активировать виртуальное окружение:

python3 -m venv env
source env/bin/activate

Установить зависимости из файла requirements.txt:

python3 -m pip install --upgrade pip
pip install -r requirements.txt

Выполнить миграции:

python manage.py makemigrations
python3 manage.py migrate

Запустить проект:

python3 manage.py runserver

Документация доступна по адресу:

http://127.0.0.1:8000/redoc/

Автор: Лера Прага и ЯП
email: abastrenie@mail.ru