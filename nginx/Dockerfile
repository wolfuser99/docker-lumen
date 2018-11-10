FROM nginx:latest

COPY site.conf /etc/nginx/conf.d/default.conf

ARG PROJECT=lumen
COPY public /var/www/${PROJECT}/public

WORKDIR /var/www/${PROJECT}/public