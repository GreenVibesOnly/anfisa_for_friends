# Anfisa for friends 
Интернет-магазин мороженого с большим каталогом от учебной компании "Анфиса".

## Функционал сайта

- Сайт имеет 2 основные страницы: каталог с отфильтрованным по категории мороженым и главная страница с избранными администратором позициями.
- Со страниц со списком позиций можно зайти в детали о конкретном мороженом, посмотреть его фотографию, описание, цену, тэги, входящие в состав топпинги и тип обёртки.
- Администратор может добавлять и убирать позиции, изменять всю их информацию, а так же выбирать, какое мороженое будет отображаться на главной странице.
- На странице "о проекте" можно посмотреть информацию о компании.

В проекте реализована админ-зона с полным набором функций для модерации контента.

## Технологии

- Python
- Django
- Djangorestframework
- HTML
- SQLite3


## Установка и запуск

Клонировать репозиторий и перейти в него в командной строке:
```
git clone <https or SSH URL>
cd anfisa_for_friends
```

Создать и активировать виртуальное окружение:
```
python3 -m venv venv
source venv/bin/activate
```

Обновить pip:
```
python3 -m pip install --upgrade pip
```

Установить библиотеки:
```
pip install -r requirements.txt
```

Создать и выполнить миграции:
```
python3 anfisa_for_friends/manage.py makemigrations
python3 anfisa_for_friends/manage.py migrate
```

Запустить сервер django:
```
python3 anfisa_for_friends/manage.py runserver
```

Проект будет доступен по адресу: http://127.0.0.1:8000/

Админ-зона по адресу: http://127.0.0.1:8000/admin/

  
## Автор проекта
[Ксения Тетерчева](https://github.com/GreenVibesOnly/) 🌿
