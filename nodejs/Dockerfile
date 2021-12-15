FROM node:17.2.0-alpine3.12
WORKDIR /usr/src/nodejs
COPY package*.json ./
RUN npm install
RUN npm install -g nodemon
COPY . .