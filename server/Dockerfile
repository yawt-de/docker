FROM php:8.2-fpm-alpine
# TODO: install additional extensions, if neccessary
RUN apk add nano sudo
RUN docker-php-ext-install mysqli pdo pdo_mysql
RUN docker-php-ext-enable pdo_mysql
# TODO: copy server files