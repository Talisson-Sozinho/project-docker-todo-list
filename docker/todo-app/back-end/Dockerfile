FROM node:16-alpine3.15

WORKDIR /app/src

COPY ./package.json ./

RUN npm install

COPY . .

EXPOSE 3001

ENTRYPOINT [ "npm" ]
CMD [ "start" ]