FROM nginx:1.13-alpine

COPY web.conf /etc/nginx/sites-available/web.c96d0576d41c.mylabserver.com

COPY admin.conf /etc/nginx/sites-available/admin.c96d0576d41c.mylabserver.com

RUN ln -s /etc/nginx/sites-available/web.c96d0576d41c.mylabserver.com /etc/nginx/sites-enabled/ \
    && ln -s /etc/nginx/sites-available/admin.c96d0576d41c.mylabserver.com /etc/nginx/sites-enabled/

EXPOSE 80
EXPOSE 443