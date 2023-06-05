FROM debian:buster-slim
MAINTAINER Tu Nombre "tucorreo@gmail.com"
RUN apt-get update  && apt-get install -y  apache2 
COPY index.html /var/www/html/
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
