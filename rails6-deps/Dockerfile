FROM ruby:2.6.1-alpine3.9

RUN apk update
RUN apk upgrade

RUN apk add --no-cache bash sudo su-exec shadow \
    yarn postgresql-client postgresql-dev \
    build-base libxml2-dev libxslt-dev
