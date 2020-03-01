# Laravel Docker Setup

This is a quick setup for your Laravel Docker Project

Comes with:

- Web App: `Laravel/PHP-7.2`
- Web Server: `nginx:stable-alpine`
- Database: `MySQL-5.7.22`

Installation

    docker-compose build && docker-compose up -d

Database migration

    docker-compose exec php php /var/www/html/artisan migrate
