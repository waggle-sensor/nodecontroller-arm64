# Node Controller - ARM64

Our current generation of Node Controller is built on the Jetson Xavier NX and runs a custom Ubuntu 18.04 Linux image.

Layered resilience is composed of bootloader and OS failover mechanisms, our own [Wagman v5 hardware](https://github.com/waggle-sensor/wagman/tree/master/boards/v5) and finally a [system watchdog](https://github.com/waggle-sensor/sage-wagman-watchdog) which ties all of these together.

The messaging and application stack is built on top of [k3s](https://k3s.io) and is provided by [Waggle Edge Stack](https://github.com/waggle-sensor/waggle-edge-stack).
