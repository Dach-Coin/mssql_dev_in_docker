# MS SQL Server Developer in Docker

## Порядок установки

1. Устанавливаем Docker (Docker Desktop для Windows или Docker для Linux)

2. При необходимости регистрируемся на https://hub.docker.com/

3. Устанавливаем в VSCode плагин Docker

4. Добавляем Registry `Docker Hub`

5. Скачиваем образ MS SQL Server Developer Edition: `docker pull mcr.microsoft.com/mssql/server`

6. Создаем каталог `./drive`

7. Компонуем контейнер:
    - `docker compose up -d` (команда для Windows)
    - `docker-compose up -d` (команда для linux, потребуется предварительная установка утилиты docker-compose, а также изменить тег `version` в docker-compose.yml: `version: "3.3"`)
