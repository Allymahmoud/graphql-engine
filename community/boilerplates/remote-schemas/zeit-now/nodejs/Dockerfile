FROM node:16.19.0

WORKDIR /server

COPY ./package.json /server/

RUN npm install

COPY . /server/

CMD ["npm", "start"]
