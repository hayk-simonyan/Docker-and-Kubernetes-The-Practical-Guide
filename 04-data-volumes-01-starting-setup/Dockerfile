FROM node

WORKDIR /nodejsapp

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "server.js"]