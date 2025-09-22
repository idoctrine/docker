FROM php:7.4-fpm

RUN apt-get update && apt-get install -y libpq-dev

RUN docker-php-ext-install pdo_mysql mysqli
RUN docker-php-ext-install pgsql pdo_pgsql


#FROM alpine
#RUN apk add --update \
#    wget \
#    curl
#RUN apk add --update \
#    php \
#    php-fpm \
#    php-pdo \
#    php-json \
#    php-openssl \
#    php-mysql \
#    php-pdo_mysql \
#    php-mcrypt \
#    php-ctype \
#    php-zlib
#RUN usermod -u 1000 www-data
#RUN rm -rf /var/cache/apk/*
#EXPOSE 9000