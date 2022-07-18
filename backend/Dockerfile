FROM node:latest

WORKDIR /backend

COPY package.json .

COPY . .

RUN npm install

CMD ["node", "backendApp.js"]