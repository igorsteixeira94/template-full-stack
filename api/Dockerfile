FROM node:lts-alpine

WORKDIR /usr/src/api

COPY package.*json .

RUN yarn

COPY . .

EXPOSE 3333

CMD ["yarn","dev:server"]



