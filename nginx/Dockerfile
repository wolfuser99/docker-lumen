FROM nginx:latest
ARG PROJECT=lumen

# COPY site.conf /etc/nginx/conf.d/default.conf
COPY public /var/www/lumen/
WORKDIR /var/www/${PROJECT}/public