FROM node:14

WORKDIR /bezkoder-app
COPY package.json .
RUN npm install
RUN npm install -g node-dev
COPY . .
CMD npm start
CMD [ "node-dev", "server.js" ]
