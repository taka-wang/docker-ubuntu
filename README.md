# docker-ubuntu [![Build Status](https://travis-ci.org/taka-wang/docker-ubuntu.svg?branch=master)](https://travis-ci.org/taka-wang/docker-ubuntu)

Dockerfile repo for development environment

## Build docker images
```bash
# ubuntu 14.04 with libzmq and czmq
docker build -t takawang/ubuntu-czmq czmq/.

# ubuntu 14.04 with libzmq, czmq and libmodbus
docker build -t takawang/ubuntu-modbus modbus/.

# ubuntu 14.04 with doxygen
docker build -t takawang/ubuntu-doxygen doxygen/.

# node.js 4.4.5 with zmq3
docker build -t takawang/node-zmq nodezmq/.

# ubuntu 14.04 with golang 1.6.x
docker build -t takawang/ubuntu-golang golang/.

# ubuntu 14.04 with golang 1.6.x and zmq
docker build -t takawang/ubuntu-gozmq gozmq/.

```