FROM php:8.2-apache

RUN apt-get update && apt-get install -y \
    zlib1g-dev libwebp-dev libpng-dev libzip-dev libpq-dev \
    && docker-php-ext-install gd zip pdo_pgsql pgsql

RUN a2enmod rewrite

EXPOSE 80
