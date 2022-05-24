FROM php:apache

RUN apt-get update; apt-get -y install vim

RUN apt-get -y install net-tools iproute2 iputils-ping curl

COPY ./index /var/www/html/

