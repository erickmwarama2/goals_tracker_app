FROM node:18

WORKDIR /app

COPY package.json package.json

RUN npm install

COPY . .

ENV DB_USER=erick

ENV DB_PASSWORD=erick

EXPOSE 80

CMD [ "npm", "start" ]