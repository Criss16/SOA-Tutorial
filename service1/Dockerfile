FROM node:lts-alpine

COPY package.json ./
COPY package-lock.json ./

RUN npm install

COPY service1 ./

ENTRYPOINT node main.js