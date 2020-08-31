Work in progress
============
This libary is a work in progress with limited testing.  

Introduction
============

This is a port of the Adafruit_CircuitPython_RFM9x library of which this repo is forked from and found here:
https://github.com/adafruit/Adafruit_CircuitPython_RFM9x

I would like to thank jerryn/jerryneedell for his assistance in getting me to this point.<br/>
https://forums.adafruit.com/viewtopic.php?f=60&t=168167&start=15

MicroPython RFM9x packet radio module for the RFM95/6/7/8 LoRa 433/915mhz radio modules.

This has been tested on various ESP32 and ESP8266 dev boards.  For detailed information on experiments with these devices, please visit the repository below:

https://github.com/nohcpy/LoPPyIOT


Usage Example
=============
See rfm9x_simpletest.py for a simple demo of the usage.

.. code-block:: python

    # Initialze RFM radio
    rfm9x = RFM9x(spi, CS, RESET, RADIO_FREQ_MHZ)
