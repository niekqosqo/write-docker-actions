FROM node:15.0.0-slim

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "node", "/src/index.js" ]
