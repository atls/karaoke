# Karaoke

## Запуск

Для всех приложений нужен `docker`

- установить [`Docker Desktop`](https://docs.docker.com/desktop/)

### Караоке

1. Запустить командой `docker compose up -d karaoke`
2. Файлы с музыкой/видео складывать в папку `media`
3. Приложение доступно по адресу `http://localhost:80`

### Камера

1. Запустить командой `docker compose up -d camera`
2. Приложение доступно по адресу `http://localhost:81`

## Остановка приложений

- Камера: `docker compose down camera`
- Караоке: `docker compose down karaoke`
