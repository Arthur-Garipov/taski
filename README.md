# Описание
Проект Taski. Предназначенный для планирования и отслеживания своих задач.

# Установка
_1. Клонировать репозиторий:_
```
git clone https://github.com/Arthur-Garipov/taski
```
_2. Перейти в папку с проектом:_
```
cd taski/backend
```
_3. Установить виртуальное окружение для проекта:_
```
python -m venv venv
```
_4. Активировать виртуальное окружение для проекта:_

# для OS Lunix и MacOS
```
source venv/bin/activate
```
# для OS Windows
```
source venv/Scripts/activate
```
_5. Установить зависимости:_
```
python -m pip install --upgrade pip
pip install -r requirements.txt
```
_6. Выполнить миграции на уровне проекта:_
```
python3 manage.py makemigrations
python3 manage.py migrate
```
_7. Запустить проект:_
```
python manage.py runserver
```
# Технологии используемые в проекте:
- Python v.3.10
- HTML
- CSS
- NGINX
- Gunicorn v.20.1

# Contributors:
- https://github.com/Arthur-Garipov
- https://github.com/yandex-praktikum
