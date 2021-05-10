FROM mysql:5.5

MYSQL_USER=adi
MYSQL_PASSWORD=parola
MYSQL_DATABASE=day7
HOSTNAME=localhost

COPY test.sql 

RUN mysql -u $MYSQL_USER -p < test.sql
RUN $MYSQL_PASSWORD

