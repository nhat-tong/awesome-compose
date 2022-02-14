FROM nginx:1.13-alpine

RUN mkdir -p /etc/nginx/sites-available \
     && mkdir -p /etc/nginx/sites-enabled

COPY web.conf /etc/nginx/sites-available/web.c96d0576d41c.mylabserver.com

COPY admin.conf /etc/nginx/sites-available/admin.c96d0576d41c.mylabserver.com

RUN ln -s /etc/nginx/sites-available/web.c96d0576d41c.mylabserver.com /etc/nginx/sites-enabled/web.c96d0576d41c.mylabserver.com \
    && ln -s /etc/nginx/sites-available/admin.c96d0576d41c.mylabserver.com /etc/nginx/sites-enabled/admin.c96d0576d41c.mylabserver.com

EXPOSE 80
EXPOSE 443