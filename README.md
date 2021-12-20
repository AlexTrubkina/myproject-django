# Лабораторная работа № 7

## Автор: Трубкина А.Ю.

### Описание работы

Команда создания проекта

```
django-admin startproject mysite
```

Запустить Django development server

```
python manage.py runserver
```

Создание приложения (будет создана папка polls)

```
python manage.py startapp polls
```

Создание БД

```
python manage.py migrate
```

Чтобы вызвать оболочку Python

```
python manage.py shell
```

**Папка polls**

В папке размещено приложение 

Структура:

```
polls/
    static/
        polls/
            images 
            style.css
    templates/
        admin/
            base_site.html
            index.html
        polls/
            detail.html
            index.html
            results.html
    __init__.py
    admin.py
    apps.py
    migrations/
        __init__.py
    models.py
    tests.py
    views.py
```

**manage.py**

Утилита командной строки, которая позволяет различными способами взаимодействовать с проектом Django.

**Папка myproject-django**

Структура:

```
myyproject-django/
        __init__.py - пустой файл, который сообщает Python, что этот каталог следует рассматривать как пакет Python
        settings.py - настройки / конфигурация для этого проекта Django
        urls.py - объявления URL для этого проекта Django
        asgi.py - начальная точка для ASGI-совместимых веб-серверов для обслуживания вашего проекта
        wsgi.py - начальная точка для WSGI-совместимых веб-серверов для обслуживания вашего проекта
```
