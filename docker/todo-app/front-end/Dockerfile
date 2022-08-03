FROM node:16-alpine3.15

WORKDIR /app

ADD ./node_modules.tar.gz .

COPY ./src/. ./src
COPY ./package.json .
COPY ./package-lock.json .
COPY ./public/. ./public
COPY ./.env .

EXPOSE 3000

ENTRYPOINT [ "npm" ]
CMD [ "start" ]