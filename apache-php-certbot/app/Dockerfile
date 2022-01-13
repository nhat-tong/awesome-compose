FROM php:7.3-apache

RUN mkdir -p /var/lib/letsencrypt

# Switch to user www-data (non root)
USER www-data

COPY --chown=www-data:www-data . /var/www/html

WORKDIR /var/www/html

EXPOSE 80
EXPOSE 443