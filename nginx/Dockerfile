FROM nginx:latest
COPY site.conf /etc/nginx/conf.d/default.conf

ARG PROJECT=lumen
WORKDIR /var/www/${PROJECT}/public
COPY public /var/www/lumen
