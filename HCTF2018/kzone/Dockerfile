FROM php:7.4.21-apache
RUN apt-get update && \
    apt-get install -y mysql-server && \
    apt-get clean
ADD www /var/www/html
EXPOSE 80
