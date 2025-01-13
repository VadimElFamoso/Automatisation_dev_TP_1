# Slim 4 API

Simple API using Slim v4 MySQL and optionnaly S3 Storage

## Run

- Create `.env` from `.env.exemple`
- Update environement variable
- run `php -S localhost:<PORT> -t ./public`

## Installation
Executer la commande suivante dans le terminal :
```bash
composer install
```
puis :
```bash
docker compose up --build
```

Une fois cela fait, le serveur web est accessible à l'adresse suivante : `http://localhost:8080/`
