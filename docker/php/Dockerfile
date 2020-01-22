FROM php:7.4.1-fpm-alpine3.11
COPY docker/php/php.ini /usr/local/etc/php/

RUN cd /usr/bin && curl -s http://getcomposer.org/installer | php && ln -s /usr/bin/composer.phar /usr/bin/composer

WORKDIR /sample-laravel-redis

RUN docker-php-ext-install pdo_mysql
