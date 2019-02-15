FROM ruby:2.6.1-alpine3.9

RUN apk update
RUN apk upgrade

RUN apk add --no-cache bash yarn postgresql-client postgresql-dev sudo \
    build-base libxml2-dev libxslt-dev

RUN adduser -u 1000 -s /bin/bash -D devel \
    && echo "devel ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

WORKDIR /home/devel

EXPOSE 3000
