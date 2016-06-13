FROM ubuntu:14.04
MAINTAINER Taka Wang <taka@cmwang.net>
 
## Set environment variable
ENV DEBIAN_FRONTEND noninteractive
RUN rm /bin/sh && ln -s /bin/bash /bin/sh

## Install required  packages
RUN apt-get update
RUN apt-get install -y graphviz doxygen


