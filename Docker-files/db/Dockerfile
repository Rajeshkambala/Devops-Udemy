FROM mysql:8.0.33
LABEL "Author"="Vprofile"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL-DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql