FROM node:slim

COPY package*.json ./

RUN npm install npm@latest -g && \
    npm install

COPY . .

CMD [ "node", "/src/index.js" ]
