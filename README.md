MAX31855
=========

Node.js package for driving the Adafruit MAX31855 thermocouple temperature amplifier. Originally built for use with Raspberry Pi, but theoretically it could work for other systems.

This library is a Node.js port and extension of Tony DiCola's Adafruit Python MAX31855 library available [here](https://github.com/adafruit/Adafruit_Python_MAX31855).

**Note:** (As of 12/29/2015) The SPI master driver is disabled by default on Raspian Linux and must be enabled before using this library
with hardware SPI. see [here](https://www.raspberrypi.org/documentation/hardware/raspberrypi/spi/README.md).

## Installation

    $ npm install max31855 --save

## Usage

    var max31855 = require('max31855');
    max31855.readTempC(function(temp) {
        console.log('Temp in degrees celsius: ', temp);
    });

## Release History

* 1.0.0 Initial release
