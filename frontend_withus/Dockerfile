# syntax=docker/dockerfile:1
FROM node:14.17.1-alpine

WORKDIR /usr/src/app

ENV CHOKIDAR_USEPOLLING=true

COPY package*.json .

RUN npm install --silent

COPY . .

CMD [ "npm", "run", "start"]