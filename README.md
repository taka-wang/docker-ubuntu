# docker-ubuntu
Dockerfile repo for development environment

## Build docker images

- ubuntu 14.04 with libzmq and czmq

    ```bash
    docker build -t takawang/ubuntu-czmq czmq/.
    ```

- ubuntu 14.04 with doxygen

    ```bash
    docker build -t takawang/ubuntu-doxygen doxygen/.
    ```

- ubuntu 14.04 psmb stack for drone.io

    ```bash
    docker build -t takawang/ubuntu-drone-psmb drone/.
    ```

- ubuntu 14.04 with golang 1.6.x

    ```bash
    docker build -t takawang/ubuntu-golang golang/.
    ```

- ubuntu 14.04 with golang 1.6.x and zmq

    ```bash
    docker build -t takawang/ubuntu-gozmq gozmq/.
    ```

- ubuntu 14.04 with libzmq, czmq and libmodbus

    ```bash
    docker build -t takawang/ubuntu-modbus modbus/.
    ```

- node.js 4.4.5 with zmq3

    ```bash
    docker build -t takawang/ubuntu-node-zmq nodezmq/.
    ```