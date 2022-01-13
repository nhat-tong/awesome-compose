FROM php:7.3-apache

# Switch to user www-data (non root)
USER www-data

COPY --chown=www-data:www-data . /var/www/html

WORKDIR /var/www/html

RUN mkdir -p .well-known/acme-challenge

EXPOSE 80
EXPOSE 443