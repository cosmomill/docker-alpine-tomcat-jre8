Alpine Tomcat Docker image
==========================

This image is based on Alpine openJDK image ([openjdk:8u121-jre-alpine](https://hub.docker.com/_/openjdk/)), which is only a 75MB image, and provides a docker image for Tomcat 8.0.
This Docker image can be used as an replacement for tomcat:8.0-jre8-alpine until [Bug #7372](https://bugs.alpinelinux.org/issues/7372) is fixed.

Usage Example
-------------

This image is intended to be a base image for your projects, so you may use it like this:

```Dockerfile
FROM cosmomill/alpine-tomcat-jre8
```

```sh
$ docker build -t my_app .
```
