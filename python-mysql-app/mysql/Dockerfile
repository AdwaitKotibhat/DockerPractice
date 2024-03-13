From mysql:latest
COPY create_tables.sql /docker-entrypoint-initdb.d/

ENV   MYSQL_DATABASE: 'db'
      MYSQL_ROOT_PASSWORD: 'root'

EXPOSE 3306
