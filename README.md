#  Internet of Things Smart City Asset Tracker Firmware Core

This IoT Firmware Core enables asset tracking functionality on your STM32L152 MCU based product using WiFi and LoRaWAN. The Asset Tracker Firmware Core enables your device to sniff WiFi signals in the smart city environment to achieve best-in-class power consumption, beating out competitor offerings that use GPS receivers.  The LoRaWAN backhaul technology enables another level of reduced power consumption compared to existing cellular technologies. This Firmware Core can enable your product enter new markets and disrupt existing ones.


## Evaluation Firmware

This IoT Asset Tracker Firmware Core runs on an easy to assemble evaluation platform based on components from ST Microelectronics.

The evaluation firmware available in this repository is free to use on the specified evaluation platform.  Without an authorization key, the firmware will run for 30 minutes before the radio shuts off.  Simply contact us to receive a free authorization key to enable unlimited evaluation or educational use. Send your device's EUI/UID as reported in the console and we will promptly generate the authorization key specific to your device.

Note that evaluation firmware provided in this repository uses a fixed and public LoRaWAN AppKey that you use to connect your device to your specific LoRaWAN application. [TBD]


## How Does The Asset Tracker Work?

The Smart City Asset Tracker Firmware Core remains asleep conserving battery energy until motion is detected. The device scans the environment for WiFi signals and transmits the captured information in a short uplink transmission.  The application server is configured to forward the packet information to the COLLOS lookup system which performs the triangulation calculations to position your device anywhere - even indoors - within the smart city.  The Asset Tracker Firmware Core performs sophisticated processing to make intelligent decisions on when to activate the use of the WiFi scanner radio and uplink transmitter to maximize battery life in real-life situations.

## Why Build Devices With Asset Tracker Firmware Cores?

You can build never-before-seen devices that are small and require infrequent battery charging and maintenance.  Entirely new markets will emerge that you can take on with your unique branding, ID and customer engagement model. Compared to competing asset tracking technologies, the Smart City Asset Tracker Firmware Core offers best-in-class power consumption, security and range.  With this system you can eliminate the use of cellular communication technology's cost, complexity and high power consumption.



