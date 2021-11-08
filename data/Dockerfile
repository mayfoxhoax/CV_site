FROM nginx

COPY ./nginx /etc/nginx/

COPY ./letsencrypt /etc/letsencrypt/

COPY ./www /var/www/

RUN mkdir /var/www/html/cpu/

RUN apt-get update; apt-get -y install vim
