# Django Hackathon Template

Basic Django template for participating in hackathons

## Local Development

### First Build Only
1. `cp .env.example .env`
2. `docker-compose up -d --build`

### Migrations
- Create Migrations
```shell
docker compose exec app python manage.py makemigrations
```
- Run migrations
```shell
docker compose exec app python manage.py migrate
```
