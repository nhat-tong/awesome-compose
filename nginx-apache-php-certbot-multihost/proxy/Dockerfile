FROM nginx:1.13-alpine

RUN mkdir -p /etc/nginx/sites-available \
     && mkdir -p /etc/nginx/sites-enabled

COPY web.conf /etc/nginx/sites-available/demo.nhat-tong.com

COPY admin.conf /etc/nginx/sites-available/admin.mysitedemo.cloudns.nz

RUN ln -s /etc/nginx/sites-available/demo.nhat-tong.com /etc/nginx/sites-enabled/ \
    && ln -s /etc/nginx/sites-available/admin.mysitedemo.cloudns.nz /etc/nginx/sites-enabled/

EXPOSE 80
EXPOSE 443