# Exchange Database

Данный репозиторий представляет dockerfile-ы, а так-же файлы миграции, которые позволяют поднять базу данных для **Exchange API**.

# ❗Важно❗
После запуска команды `make dc` стоит подождать 2-3 секунды, пока развернется контейнер с БД и только потом запускать `make migarate`:

# Поддержка

Контейнеры и миграции были разработанны и протестированны на: 
- `Windows 11 23H2`
- `Docker desktop 4.28`

## Запуск базы данных в контейнере

    make dc

## Запустить процесс применения миграций

    make migrate

