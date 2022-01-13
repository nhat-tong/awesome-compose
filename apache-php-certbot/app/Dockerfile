FROM php:7.3-apache

# Switch to user www-data (non root)
USER www-data

COPY --chown=www-data:www-data . /var/www/html

RUN mkdir -p /var/www/html/.well-known/acme-challenge

WORKDIR /var/www/html

EXPOSE 80
EXPOSE 443