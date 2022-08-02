FROM node:16-alpine3.15

WORKDIR /app/src

ADD ./node_modules.tar.gz .

COPY ./package.json .
COPY ./src .
COPY ./.env .

EXPOSE 3000

ENTRYPOINT [ "npm" ]
CMD [ "start" ]