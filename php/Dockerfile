FROM php:7.1-fpm

RUN apt-get update && apt-get install -y libssl-dev
RUN pecl install mongodb && \
    docker-php-ext-enable mongodb
