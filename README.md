MAX31855
=========

Node.js package for driving the Adafruit MAX31855 thermocouple temperature amplifier on Raspberry Pi.

## Installation

  npm install MAX31855 --save

## Usage

  var max31855 = require('max31855');
  max31855.readTempC(function(temp) {
    console.log('Temp in degrees celsius: ', temp);
  });

## Release History

* 1.0.0 Initial release
