<h1 align="center">Всем привет! Меня зовут <a href="https://vk.com/frostik89" target="_blank">Денис</a>
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Я студент Яндекс-Практикум и это мой финальный проект 9-го спринта</h3>
<hr>
<h1 align="center">Мои достижения</h1>

[![trophy](https://github-profile-trophy.vercel.app/?username=FrosTiK1989&theme=darkhub)](https://github.com/ryo-ma/github-profile-trophy)

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=FrosTiK1989&theme=dark)](https://git.io/streak-stats)
<hr>

<h1 align="center">Используемые языки в коде</h1>

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=FrosTiK1989&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
<hr>

<h1 align="center">Не много о себе</h1>
Когда то очень давно, аж в 2021 году, я задумался выучить (познать) языки програмирования. Как видно - выбор мой лег на Python. И вот прошло уже пол года, как я стал студентом и обжился своим профилем на GitHub.
За все то время, что я учусь, успел познать основы
<ol>
  <img align="center" src="https://cdn.icon-icons.com/icons2/2415/PNG/512/django_plain_logo_icon_146558.png" height="160">
  <img align="center" src="https://cdn.icon-icons.com/icons2/2530/PNG/512/python_button_icon_151925.png" height="64">
  <img align="center" src="https://cdn.icon-icons.com/icons2/2699/PNG/512/visualstudio_code_logo_icon_170248.png" height="85">
  <img align="center" src="https://cdn.icon-icons.com/icons2/2497/PNG/512/api_interface_icon_150308.png" height="85">
  <img align="center" src="https://cdn.icon-icons.com/icons2/2530/PNG/512/telegram_button_icon_151837.png" height="62">
</ol>
<hr>

### Как запустить проект

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:FrosTiK1989/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

### Примеры команд API

## GET запрос к эндпоинту

```
http://127.0.0.1:8000/api/v1/
```

Вернет список доступных url адресов

## POST запрос

```
http://127.0.0.1:8000/api/v1/jwt/create/
```

Получить токены для пользователя (обязательно указать действующего пользователя)

```
http://127.0.0.1:8000/api/v1/follow/
```

Подписаться на автора поста (обязательно указать токен и username автора)
ВНИМАНИЕ! Подписаться на самого себя нельзя!

## Полная документация

Прочитать полную документацию можно по ссылке:

```
http://127.0.0.1:8000/redoc/
```

Обязательно при запущенном сервере
