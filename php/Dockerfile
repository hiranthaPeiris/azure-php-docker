FROM php:7.4-fpm-alpine

RUN apk update --no-cache
RUN apk add --no-cache $PHPIZE_DEPS
RUN apk add --no-cache mysql-dev 
RUN docker-php-ext-install pdo pdo_mysql

