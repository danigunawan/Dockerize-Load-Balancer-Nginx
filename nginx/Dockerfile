FROM ubuntu:18.04

RUN apt-get update
RUN apt-get -y install --fix-missing \
    && apt-get -y install nginx

COPY nginx.conf /etc/nginx/nginx.conf

CMD nginx
