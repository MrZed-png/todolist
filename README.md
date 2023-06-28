
# Todolist

Dеб-сервис и набор программного обеспечения для управления задачами


## Автор

- [Danil](https://github.com/MrZed-png)


## Stack

python = "^3.11"
django = "^4.2.2"
envparse = "^0.2.0"
psycopg2-binary = "^2.9.6"

bd = PostgreSQL

## Запуск

Для Запуска необходимо создать .env в корне проекта и указать поля (поля с * обязательны)
(
SECRET_KEY=*
DEBUG=True
ALLOWED_HOSTS=
Для использование bd PostgreSQL 
POSTGRES_USER=*
POSTGRES_DB=*
POSTGRES_PASSWORD=*
POSTGRES_PORT=
) 