# Home Assistant Add-on: SiliconLabs Zigbee/OpenThread Multiprotocol Add-on

Zigbee/OpenThread Multiprotocol container for Silicon Labs based radios 
such as SONOFF ZBDongle-E.

![Supports armv7 Architecture][armv7-shield]
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]

## About

This add-on allows you to use Zigbee and OpenThread protocol simultaneous on a 
single Silicon Labs based radio. The radio needs the RCP Multi-PAN firmware 
installed to support multiple IEEE 802.15.4 Personal Area Networks (PAN). The 
addon is modified based on the Silicon Labs Multiprotocol Addon and has been 
successfully tested on the SONOFF ZBDongle-E.

[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg

### NOTICE

This project includes modified portions of code originally from a project licensed under 
the Apache License, Version 2.0:

- `Silicon Labs Multiprotocol(Modified)` were derived from 
    the Silicon Labs Multiprotocol Add-on (https://github.com/home-assistant/addons/tree/master/silabs-multiprotocol).
- `Silicon Labs Multiprotocol(Modified)` have been modified to support Simplicity SDK 2024.12.01 and include other integration changes.

Use of the code in that folder is subject to the terms of the Apache License 2.0.