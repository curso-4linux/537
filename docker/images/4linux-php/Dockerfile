FROM alpine
EXPOSE 8080

ENV PHP_INI='/etc/php81/php.ini'
ENV DB_HOST=''
ENV DB_PORT=3306
ENV DB_USER=''
ENV DB_NAME=''
ENV DB_PASS=''

RUN apk add --no-cache php-cli php-mysqli php-session php81-pecl-memcached && mkdir /app
COPY . /app
WORKDIR /app
