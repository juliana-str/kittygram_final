#Kittygram

### Описание:

Kittygram — социальная сеть для обмена фотографиями любимых питомцев.

### Установка:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://git@github.com:juliana-str/kittygram_final.git
```

```
cd backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
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

### Примеры запросов:
Запрос на регистрацию нового пользователя:

```
https://my-kittygram.zapto.org/signin
```

Запрос на добавление нового котика:

```
https://my-kittygram.zapto.org/cats/add
```
