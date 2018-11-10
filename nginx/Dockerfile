FROM nginx:latest
ARG PROJECT=lumen
COPY ./public /var/www/${PROJECT}/public
COPY ./nginx/site.conf /etc/nginx/conf.d/default.conf
WORKDIR /var/www/${PROJECT}/public