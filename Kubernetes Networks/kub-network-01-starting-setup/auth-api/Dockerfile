FROM node:14-alpine

WORKDIR /app

COPY package*.json /app

RUN npm install

COPY . /app

EXPOSE 80

CMD ["node", "auth-app.js"]