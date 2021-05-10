FROM mysql:5.7

ENV MYSQL_USER=adi
ENV MYSQL_PASSWORD=parola
ENV MYSQL_DATABASE=day7
ENV HOSTNAME=localhost

RUN mkdir test
WORKDIR /test

COPY test.sql /test/test.sql 
