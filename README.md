О проекте
Учебный проект для группы Python26_Ev

Настройка проекта
Создайте виртуальное окружение
python3 -m venv venv
Активируйте виртуальное окружение
source venv/bin/activate
Используйте pip для установки библиотек
pip install -r requirements-dev.txt
Создайте базу данных в PostgreSQL
createdb <db_name>
Создайте файл .env и заполните данные как в .env.template
cat .env.template > .env
Проведите миграции
python3 manage.py migrate
Создайте супер-пользователя
python3 manage.py createsuperuser
Запустите сервер
python3 manage.py runserver
Полезные ссылки
Django

DRF

PostgreSQL

Swagger
