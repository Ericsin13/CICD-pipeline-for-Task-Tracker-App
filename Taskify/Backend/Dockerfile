FROM node:23-alpine

WORKDIR /app

COPY Package*.json ./

RUN npm install 

COPY . .

EXPOSE 5000

CMD [ "node", "index.js" ]

