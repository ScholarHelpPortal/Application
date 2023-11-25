FROM node:slim

WORKDIR /usr/src/frontend

COPY package.json ./

RUN npm install

COPY  . .

EXPOSE 3000

CMD [ "sh", "-c" , "npm start" ]