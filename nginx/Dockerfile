FROM nginx:latest
ARG PROJECT=lumen
COPY nginx/site.conf /etc/nginx/conf.d/default.conf
COPY public /var/www/lumen/public
WORKDIR /var/www/${PROJECT}/public