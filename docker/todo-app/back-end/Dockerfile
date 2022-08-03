FROM node:16-alpine3.15

WORKDIR /app

ADD ./node_modules.tar.gz .

COPY ./src/. ./src
COPY package.json .
COPY package-lock.json .

EXPOSE 3001

ENTRYPOINT [ "npm" ]
CMD [ "start" ]