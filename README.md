# aa30zero-wifi
HF antenna analyzer using esp8266 nodemcu

**WORK IN PROGRESS**

## Goal

Create a battery powered portable device with which you can make measurements. Measurements can be downloaded via WIFI and replayed to Antscope or converted to csv.

## user interface

2 RGB leds and 2 buttons:
* WIFI button, WIFI LED
* Measuement button, Measurement LED

### WIFI

Short press the WIFI button to connect or disconnect from WIFI.
Long press the WIFI button to enter WIFI end-user-setup.

WIFI LED indicates status:
* blinking blue: connecting to an AP (a wifi network)
* blue: connected to an AP
* red: failed to connect to an AP
* yellow: in end user setup (see https://nodemcu.readthedocs.io/en/latest/en/modules/enduser-setup/ )
* magenta: error in end user setup

w sumie to tyle have fun



