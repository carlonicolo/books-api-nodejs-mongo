FROM node:14

WORKDIR /books-api-nodejs-mongo
COPY package.json .
RUN npm install
COPY . .
CMD npm start
