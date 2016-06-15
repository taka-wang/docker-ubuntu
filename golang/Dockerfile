FROM ubuntu:14.04
MAINTAINER Taka Wang <taka@cmwang.net>

ENV DEBIAN_FRONTEND noninteractive
ENV VERSION 1.6.2
ENV OS linux
ENV ARCH amd64
RUN rm /bin/sh && ln -s /bin/bash /bin/sh

# update and wget
RUN apt-get -qq update && \
    apt-get -qqy install wget git

# Install golang

RUN wget https://storage.googleapis.com/golang/go$VERSION.$OS-$ARCH.tar.gz && \
    tar -C /usr/local -xzf go$VERSION.$OS-$ARCH.tar.gz && \
    rm go$VERSION.$OS-$ARCH.tar.gz

# env variables
RUN mkdir /go
ENV GOPATH /go
ENV PATH=$PATH:/usr/local/go/bin:$GOPATH/bin

WORKDIR /go