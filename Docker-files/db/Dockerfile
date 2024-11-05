FROM mysql:8.0.33
LABEL "project"="vprofile"
LABEL "Author"="nawaz"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-enterypoint-initdb.d/db_backup.sql

EXPOSE 3306
