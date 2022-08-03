FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

ADD ./node_modules.tar.gz .

COPY ./package.json .
COPY ./package-lock.json .
COPY ./e2e/. ./e2e
COPY ./jest.config.js .

ENTRYPOINT [ "npm" ]
CMD [ "test" ]