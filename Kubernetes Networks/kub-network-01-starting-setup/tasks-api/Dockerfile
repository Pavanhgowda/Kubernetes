FROM node:14-alpine

WORKDIR /app

COPY package*.json /app

RUN npm install

COPY . /app

ENV AUTH_ADD=auth
ENV TASKS_FOLDER=tasks

EXPOSE 8000

CMD ["node","tasks-app.js"]

