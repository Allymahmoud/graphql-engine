FROM node:21.2-alpine3.18

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY ./* /app/

CMD ["npm", "start"]
