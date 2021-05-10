FROM node:latest

RUN mkdir day7
WORKDIR /day7

COPY server.js /day7/server.js

RUN npm install express

WORKDIR /usr/local
COPY ./src .

CMD [ "node", "server.js" ]
EXPOSE 3000
