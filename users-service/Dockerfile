FROM node:16.20.0

WORKDIR /app

COPY package.json .
COPY package-lock.json .

RUN npm install

COPY src src
COPY conf conf

ENV ENV=prod

EXPOSE 3000
ENTRYPOINT [ "npm", "start" ]
