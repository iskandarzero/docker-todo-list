FROM mjgargani/puppeteer:trybe1.0
ADD ./node_modules.tar.gz .
WORKDIR /tests
COPY . .
ENTRYPOINT [ "npm", "test" ] 