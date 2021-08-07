# FastAPIProject
fast api tutorial

## Установка проекта

- Клонируем проект `git clone https://github.com/VasiliySilver/FastAPIProject.git`

- `pip install -r requirements.txt`

### Создаем проект
- создаем папку в которой будем работать `mkdir workdir`
- `cd wordir`
- Клонируем проект `git clone https://github.com/VasiliySilver/FastAPIProject.git`
- `cd FastAPIProject`

### Виртуальное окружение
- `python -m pip install virtualenv`
- `virtualev venv`

Активация venv
  
>- for Linux - `source venv\bin\activate`
>- for Windows - `venv\Scripts\activate.bat`

Деактивация venv

> `deactivate`


## Сервер

- убедиться что установлен uvicorn
- `pip install uvicorn[standard]`
- Запускаем сервер командой - `uvicorn main:app --reload`

## Проверить работу

- [http://127.0.0.1:8000/items/5?q=somequery](http://127.0.0.1:8000/items/5?q=somequery)
```JSON
{"item_id": 5, "q": "somequery"}
```


## Swagger

- [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

## ReDoc

- [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)



