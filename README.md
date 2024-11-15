# Kittygram Final Project ![Статус](https://github.com/YakovlevKir/kittygram_final/actions/workflows/main.yml/badge.svg)

## Описание проекта

Kittygram — это веб-приложение для размещения и просмотра изображений кошек, созданное с использованием Django и React. Приложение включает возможности для загрузки изображений, их просмотра и администрирования через панель управления.  

## Стек технологий

- **Backend**: Django, Django Rest Framework

- **Frontend**: React

- **Контейнеризация**: Docker, Docker Compose

- **CI/CD**: GitHub Actions

- **Веб-сервер**: Nginx

## Развертывание проекта

Для локальной разработки создайте файл `.env` с необходимыми переменными:

```env
POSTGRES_DB=...
POSTGRES_USER=...
POSTGRES_PASSWORD=...
DB_NAME=...
DB_HOST=...
DB_PORT=...
DEBUG=True
SECRET_KEY=...
ALLOWED_HOSTS=localhost
```

1. Клонируйте репозиторий:
```bash
git clone https://github.com/YakovlevKir/kittygram_final.git
cd kittygram_final
```

2. Запустите проект с использованием Docker Compose:

```bash
docker-compose -f docker-compose.production.yml up --build
```

3. Откройте приложение в браузере по адресу: [http://localhost:8000](http://localhost:8000)

## Автор

- **Автор**: Yakovlev Kirill
