FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app/src

ADD ./node_modules.tar.gz .

COPY ./package.json .
COPY ./e2e .
COPY ./jest.config.js .

ENTRYPOINT [ "npm" ]
CMD [ "test" ]