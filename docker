FROM docker.io/ubuntu

ENV DEBIAN_FRONTEND=noninteractive 

RUN apt-get update 

RUN apt-get install -y apache2

COPY index.html /var/www/html

EXPOSE 80

CMD apachect1 -D FOREGROUND

