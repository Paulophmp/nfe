FROM php:7.2.5-fpm

WORKDIR "/app"

RUN apt-get update

RUN docker-php-ext-install mbstring pdo \
    && pecl install xdebug \
    && docker-php-ext-enable xdebug