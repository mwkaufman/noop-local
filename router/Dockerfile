FROM node:8-alpine
WORKDIR /router
COPY package.json package.json
RUN npm install
COPY *.js .
COPY lib/ lib/
CMD node server.js
