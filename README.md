# espoilgauge

This is an [esphome](https://esphome.io/) project to monitor oil level in an oil tank.
It's configured to use an esp32-c6 but could be adapted for any esp32.
The US-100 sensor device is used to measure distance between the top of the tank and the remaining oil.
This sensor was choosen because it uses 3.3v logic as the esp32 and should run on the long term.
