FROM php:5.6-apache
COPY php.ini /usr/local/etc/php

MAINTAINER Tarun Mohanty

COPY src /var/www/data
COPY Docker/vhost.conf /etc/apache2/sites-available/000-default.conf
RUN chown -R www-data:www-data /srv/app && a2enmod rewrite


