FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app/src

COPY ./package.json ./

RUN npm install

COPY . .

EXPOSE 3000

ENTRYPOINT [ "npm" ]
CMD [ "test" ]