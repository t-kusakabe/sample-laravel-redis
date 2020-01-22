FROM node:13.6.0-alpine3.11

WORKDIR /sample-laravel-redis

RUN apk add --no-cache \
      build-base

ADD package.json yarn.lock ./
RUN yarn
