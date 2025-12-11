# django_sprint4
## Установка:

1. Создание и активация виртуального окружения

```
python -m venv venv
source venv/Scripts/activate
```

2. Установка зависимостей

```
pip install -r requirements.txt
```

3. Перейти в папку проекта blogicum и запустить его:

```
cd blogicum
./manage.py migrate
./manage.py loaddata db.json
./manage.py runserver
```

4. Перейти на локальный сервер:

```
http://127.0.0.1:8000/
```

5. Перейти в панель администратора:

```
http://127.0.0.1:8000/admin/
```