FROM node:12.18.3

RUN mkdir day7
WORKDIR /day7

COPY server.js /day7/server.js

COPY test.sql /day7/test.sql

RUN npm install express

CMD [ "node", "server.js" ]
