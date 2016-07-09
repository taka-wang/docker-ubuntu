# docker-ubuntu [![Build Status](https://travis-ci.org/taka-wang/docker-ubuntu.svg?branch=master)](https://travis-ci.org/taka-wang/docker-ubuntu)

Dockerfile repo for development environment

## Build docker images

[![](https://imagelayers.io/badge/takawang/ubuntu-czmq:latest.svg)](https://imagelayers.io/?images=takawang/ubuntu-czmq:latest 'Get your own badge on imagelayers.io')
```bash
# ubuntu 14.04 with libzmq and czmq
docker build -t takawang/ubuntu-czmq czmq/.
```

[![](https://imagelayers.io/badge/takawang/ubuntu-doxygen:latest.svg)](https://imagelayers.io/?images=takawang/ubuntu-doxygen:latest 'Get your own badge on imagelayers.io')
```bash
# ubuntu 14.04 with doxygen
docker build -t takawang/ubuntu-doxygen doxygen/.
```


```bash
# ubuntu 14.04 psmb stack for drone.io
docker build -t takawang/ubuntu-drone-psmb drone/.
```

[![](https://imagelayers.io/badge/takawang/ubuntu-golang:latest.svg)](https://imagelayers.io/?images=takawang/ubuntu-golang:latest 'Get your own badge on imagelayers.io')
```bash
# ubuntu 14.04 with golang 1.6.x
docker build -t takawang/ubuntu-golang golang/.
```

[![](https://imagelayers.io/badge/takawang/ubuntu-gozmq:latest.svg)](https://imagelayers.io/?images=takawang/ubuntu-gozmq:latest 'Get your own badge on imagelayers.io')
```bash
# ubuntu 14.04 with golang 1.6.x and zmq
docker build -t takawang/ubuntu-gozmq gozmq/.
```

[![](https://imagelayers.io/badge/takawang/ubuntu-modbus:latest.svg)](https://imagelayers.io/?images=takawang/ubuntu-modbus:latest 'Get your own badge on imagelayers.io')
```bash
# ubuntu 14.04 with libzmq, czmq and libmodbus
docker build -t takawang/ubuntu-modbus modbus/.
```

[![](https://imagelayers.io/badge/takawang/ubuntu-node-zmq:latest.svg)](https://imagelayers.io/?images=takawang/ubuntu-node-zmq:latest 'Get your own badge on imagelayers.io')
```bash
# node.js 4.4.5 with zmq3
docker build -t takawang/ubuntu-node-zmq nodezmq/.
```