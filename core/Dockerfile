FROM node:lts-alpine

WORKDIR /home/node/core/

COPY ./app /home/node/core/

WORKDIR /home/node/core/app

RUN npm install

EXPOSE 3000