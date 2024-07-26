FROM php:8.2-fpm-alpine

RUN apk add icu-dev
RUN apk add zlib-dev
RUN apk add libpng-dev
RUN docker-php-ext-configure intl
RUN docker-php-ext-install intl
RUN docker-php-ext-enable intl
RUN docker-php-ext-install mysqli
# RUN docker-php-ext-configure gd --with-freetype --with-jpeg
RUN docker-php-ext-install gd
RUN docker-php-ext-enable gd

# expose 9000