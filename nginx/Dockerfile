FROM nginx:latest

ARG PROJECT=laravel5
WORKDIR /var/www/${PROJECT}/public
COPY public /var/www/${PROJECT}/public

COPY site.conf /etc/nginx/conf.d/default.conf