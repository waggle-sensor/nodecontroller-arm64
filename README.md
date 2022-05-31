# Node Controller

The Node Controller is a single-board Linux computer providing encrypted TCP/IP messaging, data caching, node health monitoring, and cybersecurity tools including cryptokey management and signed software. While the above tasks are its main priority, through container-based isolation technologies, the node controller is also available to run user applications on the dedicated CPU-GPU resources.

Our current generation of Node Controller is built on the Jetson Xavier NX and runs a custom, Ubuntu 18.04 Linux OS.

Layered resiliency is provided through bootloader and OS failover mechanisms, our own [Wagman v5 hardware](https://github.com/waggle-sensor/wagman/tree/master/boards/v5) and a [system watchdog](https://github.com/waggle-sensor/sage-wagman-watchdog) which ties all of these together.

The messaging and application stack is provided by [Waggle Edge Stack](https://github.com/waggle-sensor/waggle-edge-stack).
