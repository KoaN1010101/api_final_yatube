Описание
Полноценный REST API для социальной сети Yatube. 

Технологии:
Python 3.7
Django 2.2
Django REST Framework
JWT

Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

git@github.com:KoaN1010101/api_final_yatube.git
cd api_final_yatube
Cоздать виртуальное окружение:

python -m venv venv
Aктивировать виртуальное окружение:

source venv/Scripts/activate
Установить зависимости из файла requirements.txt:

python -m pip install --upgrade pip
pip install -r requirements.txt
Выполнить миграции:

python manage.py migrate
Запустить проект:

python manage.py runserver

