FROM seo4ajax/phantomjs

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

ONBUILD COPY . /usr/src/app

CMD [ "phantomjs", "index.js" ]