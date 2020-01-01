FROM elixir:1.9.4

RUN apt-get update
RUN apt-get upgrade

RUN apt-get install -y vim inotify-tools
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -
RUN apt-get install -y nodejs
RUN mix archive.install --force hex phx_new 1.4.11
