# OIAX Docker Image for Rails 6 development

## Building a docker image

```
$ docker build -t oiax/rails6-deps .
```

## Starting a container for inspection

```
$ docker run -itd --name rails6-deps oiax/rails6-deps:latest
```

## Logging into the conatiner

```
$ docker exec -it rails6-deps bash
```

## Destroying the container

```
$ docker rm rails6-deps
```
