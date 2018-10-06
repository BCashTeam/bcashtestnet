FROM debian:stretch
LABEL maintainer="BCash Developers <dev@bcash.org>"
LABEL description="Dockerised BCashCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
