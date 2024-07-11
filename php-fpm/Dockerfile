FROM php:8.2-fpm-alpine

RUN apk add icu-dev
RUN docker-php-ext-configure intl
RUN docker-php-ext-install intl
RUN docker-php-ext-enable intl
RUN docker-php-ext-install mysqli

# expose 9000