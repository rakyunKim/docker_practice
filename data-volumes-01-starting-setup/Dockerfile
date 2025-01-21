FROM node:latest

WORKDIR /app

COPY package.json /app

COPY . /app

RUN npm install

ENV PORT 80

EXPOSE ${PORT}

CMD [ "start", "start" ]