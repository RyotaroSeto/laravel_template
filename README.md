## DEV

### PHP

php:8.0

composer:2.1

### nginx

nginx:1.20-alpine

### mysql

mysql:8.0

### node

node:16-alpine

## Usage

## 構築手順

git clone https://github.com/RyotaroSeto/laravel_template.git

docker compose up -d

docker compose exec app bash

composer update

docker compose exec web ash

npm install && npm run dev
