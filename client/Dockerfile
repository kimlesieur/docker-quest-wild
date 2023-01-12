# Dockerfile
FROM node:lts-alpine

RUN mkdir /client
WORKDIR /client
COPY package*.json ./
RUN npm i
COPY src src
COPY public public

CMD npm start