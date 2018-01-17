FROM mysql:5.6

RUN set -ex \
    && usermod -u 1000 mysql \
    && groupmod -g 1000 mysql \
    && chown -R mysql:mysql /var/lib/mysql
