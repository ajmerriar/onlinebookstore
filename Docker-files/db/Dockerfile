FROM mysql:8.0.34

ENV MYSQL_ROOT_PASSWORD="password"
ENV MYSQL_DATABASE="onlinebookstore"

#mysql -uroot -p"$MYSQL_ROOT_PASSWORD"

ADD Docker-files/db/db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql

EXPOSE 3306