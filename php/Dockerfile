FROM php:rc-cli-alpine

WORKDIR /app

COPY ./ /app

RUN chown -R www-data:www-data /app

USER www-data

CMD ["php", "hello.php"]