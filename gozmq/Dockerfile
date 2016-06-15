FROM takawang/ubuntu-golang
MAINTAINER Taka Wang <taka@cmwang.net>
 
## Set environment variable
ENV DEBIAN_FRONTEND noninteractive

## Install deps
RUN apt-get update && \
    apt-get install -y libzmq3-dev

WORKDIR /go
RUN go get github.com/taka-wang/zmq3