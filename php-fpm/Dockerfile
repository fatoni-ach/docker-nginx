FROM php:8.2-fpm-alpine

RUN apk add icu-dev
RUN docker-php-ext-configure intl
RUN docker-php-ext-install intl
RUN docker-php-ext-enable intl

# expose 9000