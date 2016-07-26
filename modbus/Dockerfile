FROM takawang/czmq:x86
MAINTAINER Taka Wang <taka@cmwang.net>
 
## Set environment variable
ENV DEBIAN_FRONTEND noninteractive
ENV MB_GIT https://github.com/stephane/libmodbus.git

## Install libmodbus
RUN cd / && \
    git clone $MB_GIT && \
    cd libmodbus && \
    ./autogen.sh && \
    ./configure --prefix=/usr && \
    make && \
    make install && \
    ldconfig && \
    rm -rf /libmodbus
