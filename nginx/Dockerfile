FROM nginx:latest
RUN /bin/bash -c 'ls -lha /var/lib/docker/tmp/'
COPY site.conf /etc/nginx/conf.d/default.conf
COPY public /var/www/lumen/public
ARG PROJECT=lumen
WORKDIR /var/www/${PROJECT}/public