FROM php:apache

LABEL maintainer="NeuronAddict https://github.com/neuronaddict"

ADD https://github.com/robocoder/rips-scanner/archive/0.55.tar.gz /tmp/rips.tar.gz

RUN tar -xf /tmp/rips.tar.gz -C /tmp && cp -r /tmp/rips-scanner-0.55/* /var/www/html
