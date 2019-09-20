FROM ruby:2.6.4-alpine3.9

RUN apk update
RUN apk upgrade

RUN apk add --no-cache \
    bash git vim openssh openssl yarn sudo su-exec shadow tzdata \
    postgresql-client postgresql-dev \
    build-base libxml2-dev libxslt-dev
