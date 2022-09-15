FROM node:lts-alpine3.16

WORKDIR /usr/src/todo-app

COPY package*.json ./

COPY . .

EXPOSE 3001

CMD [ "npm", "start" ]
