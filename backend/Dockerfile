FROM node:12.18.4-alpine

WORKDIR /app/

ADD package*.json ./

RUN npm install

ADD app.js .

CMD ['node', 'app.js']

EXPOSE 5000