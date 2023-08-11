FROM php:8.1-fpm-alpine

# install composer
# curlの進捗は非表示、エラーは表示する
RUN curl -sS https://getcomposer.org/installer | php
RUN mv composer.phar /usr/local/bin/composer
