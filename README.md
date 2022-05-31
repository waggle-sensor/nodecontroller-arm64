# Node Controller

The Node Controller is a single-board Linux computer providing encrypted TCP/IP messaging, data caching, node health monitoring, and cybersecurity tools including cryptokey management and signed software. While the above tasks are its main priority, through container-based isolation technologies, the node controller is also available to run user applications on the dedicated CPU-GPU resources.

Our current generation of Nvidia Jetson based Node Controller is primarily composed of:

* Jetson Xavier NX
* Ubuntu 18.04 Based OS(TODO add link)
* Resilience Support:
    * [Wagman v5](https://github.com/waggle-sensor/wagman)
    * [Wagman Watchdog](https://github.com/waggle-sensor/sage-wagman-watchdog)
* Application Stack
    * [Waggle Edge Stack](https://github.com/waggle-sensor/waggle-edge-stack)
