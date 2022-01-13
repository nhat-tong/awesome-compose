FROM php:7.3-apache

# Enable mod_rewrite & ssl
RUN a2enmod rewrite \
    && a2enmod ssl \
    && a2ensite default-ssl

# Switch to user www-data (non root)
USER www-data

COPY --chown=www-data:www-data . /var/www/html

WORKDIR /var/www/html

EXPOSE 80
EXPOSE 443