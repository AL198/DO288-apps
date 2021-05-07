FROM node:12.18.3

RUN mkdir day6
WORKDIR /day6

COPY server.js /day6/

RUN npm install express

CMD [ "node", "server.js" ]
EXPOSE 3000
