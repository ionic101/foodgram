# Foodgram - Платформа для обмена рецептами

Сайт с кулинарными рецептами

## Запуск

### 1. Создание .env
Необходимо создать .env файл в корне проекта.
Пример `.env` файла приведен в `.env.example`

### 2. Запуск Docker
```bash
cd infra
docker-compose up -d
```

### 3. Загрузка фикстур
```bash
docker compose exec backend python manage.py loaddata data/dump.json
```


### 4. Тестирование
Сайт будет доступен по адресу http://localhost/
