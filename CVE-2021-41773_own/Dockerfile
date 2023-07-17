FROM httpd:2.4.49-buster

RUN mkdir -p /var/www/html && chown -R daemon:daemon /var/www/html

COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf