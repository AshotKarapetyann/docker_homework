FROM ubuntu:20.04

FROM node:current

WORKDIR /app

COPY . /app

COPY package.json package-lock.json /app/

RUN npm install

RUN npm install nodemon

CMD npm run start