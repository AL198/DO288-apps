FROM mysql:5.5

MYSQL_USER=adi
MYSQL_PASSWORD=parola
MYSQL_DATABASE=day7
HOSTNAME=localhost

RUN mkdir test && \
WORKDIR /test  && \

COPY test.sql /test/test.sql && \

RUN mysql -u $MYSQL_USER -p < test.sql && \
RUN $MYSQL_PASSWORD

