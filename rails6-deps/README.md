# OIAX Docker Image for Rails 6 development

## Summary

* Alpine 3.9
* Ruby 2.6.1
* PostgreSQL 11.1
* Node.js 10.14.2
* Yarn 1.12.3
* Rubygems 3.0.1
* Bundler 1.17.2

## Building a docker image

```
$ docker build -t oiax/rails6-deps .
```

## Starting a container for inspection

```
$ docker run -itd --name rails6-deps oiax/rails6-deps:latest
```

## Listing containers

```
$ docker ps    # Running containers
$ docker ps -a # All containers
```

## Logging into the conatiner

```
$ docker exec -it --user devel rails6-deps bash
```

## Stopping the container

```
$ docker stop rails6-deps
```

## Destroying the container

```
$ docker rm rails6-deps
```
