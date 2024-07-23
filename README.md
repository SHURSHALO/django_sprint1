# Blogicum

> Blogicum - это блоговая платформа на базе Django,
которая позволяет создавать и публиковать блоги. 
Она предоставляет простой и интуитивно понятный интерфейс для управления записями, 
категориями и статическими страницами.

# Установка

1. Клонируйте репозиторий на свою локальную машину:
```
git clone git@github.com:SHURSHALO/Blogicum_sprint1.git
```
2. Перейдите в директорию проекта:
```
cd Blogicum_sprint1
```
3. Создайте и активируйте виртуальное окружение (опционально):
```
py -3.9 -m venv venv
```
```
source venv/Scripts/activate
```
4. Установите необходимые зависимости:
```
pip install -r requirements.txt
```
5. Примените миграции базы данных:
```
cd blogicum
```
```
python manage.py migrate
```

7. Запуск
```
python manage.py runserver
```

Откройте веб-браузер и перейдите по адресу http://localhost:8000/, чтобы получить доступ к приложению Blogicum.
