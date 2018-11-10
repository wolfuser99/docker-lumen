FROM nginx:latest
RUN ls
COPY site.conf /etc/nginx/conf.d/default.conf

COPY public /var/www/lumen/public

ARG PROJECT=lumen
WORKDIR /var/www/${PROJECT}/public