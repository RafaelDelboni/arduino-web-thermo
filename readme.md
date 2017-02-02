Arduino Web Thermometer
===================


Simple project I created to measure a server room temperature and give back the results in a HTTP endpoint via JSON.

----------


Hardware
-------------

List of hardware I used in the project
> - Arduino Duemilanove **AtMega328**
> - Ethernet Shield **ENC28J60**
> - Thermistor **NTC 102**
> - Resistor **10k**

#### <i class="icon-file"></i> Wiring
![alt tag](https://raw.githubusercontent.com/rafaeldelboni/arduino-web-thermo/master/wires.png)

----------

Library
-------------------

I used this [fork of the library UIPEthernet library][1] to use my old Ethernet Shield on the newest version of the Arduino IDE.

  [1]: https://github.com/argami/arduino_uip
