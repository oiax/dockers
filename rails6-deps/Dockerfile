FROM ruby:2.6.1-alpine3.9

RUN apk update
RUN apk upgrade
RUN apk add bash yarn postgresql-client sudo

RUN adduser -u 1000 -s /bin/bash -D devel \
    && echo "devel ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

WORKDIR /tmp

EXPOSE 3000
