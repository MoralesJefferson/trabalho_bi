FROM mysql:8.0.16

ENV MYSQL_ROOT_PASSWORD 1234

COPY ./db_fat.dim.sql /docker-entrypoint-initdb.d/01-db_fat.dim.sql

