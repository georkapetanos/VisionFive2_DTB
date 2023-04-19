### Device Tree Overlay blob and source file for Starfive VisionFive 2 custom hardware interface.

#### Enabled Interfaces

* UART1 -> /dev/ttyS1, tx-pin: GPIO63 (35), rx-pin: GPIO60 (37)
* UART2 -> /dev/ttyS2, tx-pin: GPIO61 (38), rx-pin: GPIO44 (40)

#### Other changes

* Change ack led default trigger to "none", in order to avoid contant blinking
