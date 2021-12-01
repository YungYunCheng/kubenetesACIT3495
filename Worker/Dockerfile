FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install httpd -y
RUN apt-get install php -y

CMD /usr/sbin/httpd -DFOREGROUND

EXPOSE 8888

COPY index.html /var/www/html