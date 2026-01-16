FROM node:16.20.2

WORKDIR /server

COPY ./package.json /server/

RUN npm install

COPY . /server/

CMD ["npm", "start"]
