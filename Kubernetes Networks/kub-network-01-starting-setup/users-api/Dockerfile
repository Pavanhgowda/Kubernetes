FROM node:14-alpine

WORKDIR /app

COPY package*.json /app

RUN npm install

COPY . /app

ENV AUTH_ADD=host
ENV AUTH_SERVICE_SERVICE_HOST=auth

EXPOSE 8080

CMD ["node", "users-app.js"]