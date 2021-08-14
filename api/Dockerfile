
FROM node:12.16.0-slim

RUN mkdir -p /usr/src/nivo-api

WORKDIR /usr/src/nivo-api

COPY . .

RUN yarn install --frozen-lockfile --production

ENTRYPOINT ["yarn",  "start"]