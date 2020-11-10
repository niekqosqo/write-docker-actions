FROM node:slim

COPY package*.json ./

RUN npm cache clean --force && \
    npm install -g -s --no-progress yarn && \
    yarn install

COPY . .

CMD [ "node", "/src/index.js" ]
