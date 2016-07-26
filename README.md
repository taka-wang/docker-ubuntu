# docker files

Dockerfile repo for development environment

## Build docker images

- libzmq and czmq

    ```bash
    docker build -t takawang/czmq:x86 czmq/.
    ```

- doxygen

    ```bash
    docker build -t takawang/doxygen:x86 doxygen/.
    ```

- golang 1.6.x

    ```bash
    docker build -t takawang/golang:x86 golang/.
    ```

- golang 1.6.x and zmq

    ```bash
    docker build -t takawang/gozmq:x86 gozmq/.
    ```

- libzmq, czmq and libmodbus

    ```bash
    docker build -t takawang/modbus-env:x86 modbus/.
    ```

- node.js 4.4.5 with zmq3

    ```bash
    docker build -t takawang/node-zmq nodezmq/.
    ```