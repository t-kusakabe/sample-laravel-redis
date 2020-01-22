FROM mysql:5.7

ENV MYSQL_USER root

COPY ./docker/mysql/mysql.cnf /etc/mysql/config.d/mysql.cnf
COPY ./docker/mysql/init.sql /docker-entrypoint-initdb.d/init.sql
