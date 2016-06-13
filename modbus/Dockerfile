FROM takawang/ubuntu-czmq
MAINTAINER Taka Wang <taka@cmwang.net>
 
## Set environment variable
ENV DEBIAN_FRONTEND noninteractive
ENV MB_GIT https://github.com/stephane/libmodbus.git

## Install libmodbus
WORKDIR  /
RUN git clone $MB_GIT
WORKDIR  /libmodbus
RUN ./autogen.sh && \
    ./configure && \
    make && \
    make install && \
    ldconfig
