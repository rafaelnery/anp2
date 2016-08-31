FROM php:fpm-alpine

 RUN docker-php-ext-install pgsql pdo pdo_pgsql opcache zip
 RUN apk update
 RUN apk add -u bash
