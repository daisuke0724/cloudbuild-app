FROM php:7.2-fpm-alpine
RUN docker-php-ext-install -j$(nproc) pdo_mysql

COPY docker/php/php.ini /usr/local/etc/php/php.ini
COPY src /var/www
