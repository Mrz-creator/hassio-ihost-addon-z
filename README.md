# Hassio iHost Add-ons

## About
This repository contains a set of Home Assistant add-ons developed specifically for **SONOFF iHost**.

## Requirements
To use these add-ons, the following requirements must be met:

* Home Assistant must be running on **iHost**, installed from a **pre-flashed microSD card**.
  👉 For setup instructions, please refer to the [Operation Guide](https://github.com/iHost-Open-Source-Project/ha-operating-system?tab=readme-ov-file#readme)


## Installation
1. Go to the Add-on Store → Click the **More** button (⋮) in the upper-right corner → Select **Repositories**  
2. Paste the following URL:  
   [https://github.com/iHost-Open-Source-Project/hassio-ihost-addon](https://github.com/iHost-Open-Source-Project/hassio-ihost-addon)  
3. Or, simply click the button below to add it automatically:

[![Add Repository](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2FiHost-Open-Source-Project%2Fhassio-ihost-addon)

## 🔄 Updating Repository

If you can only see part of the add-ons after adding this repository, it might be due to outdated local cache.  
To refresh:

1. Go to the Add-on Store  
2. Click the **More** button (⋮) in the upper-right corner  
3. Click **Check for updates**

This will force Home Assistant to reload the latest add-on list from all configured repositories.

## Available Add-ons

### iHost Hardware Control

This add-on exposes iHost's hardware (buttons, RGB indicators, LED strips) as entities in Home Assistant, enabling flexible automations and hardware integration.

[Documentation →](https://github.com/iHost-Open-Source-Project/hassio-ihost-addon/blob/master/hassio-ihost-hardware-control/DOCS.md)

---

### SONOFF Dongle Flasher for iHost

Flash and upgrade the built-in MG21 Zigbee coordinator firmware directly from Home Assistant.  
Supports switching between Zigbee and Thread firmware via a simple web interface.

[Documentation →](https://github.com/iHost-Open-Source-Project/hassio-ihost-addon/blob/master/hassio-ihost-sonoff-dongle-flasher/DOCS.md)

---
### Node-RED

This add-on is a standalone packaged version of Node-RED, exclusively designed to support the linux/arm/v7 architecture. It has been packaged by SONOFF, specifically tailored for iHost users

[Documentation →](https://github.com/iHost-Open-Source-Project/hassio-ihost-addon/blob/master/hassio-ihost-node-red/README.md)

---

### Matter Bridge for iHost

Matter Bridge add-on exposes Home Assistant devices as Matter-enabled devices, enabling them to be integrated with Matter platforms, such as Apple Home, Google Home, and Amazon Alexa. This add-on is based on iHost Matter Bridge and has passed Matter certification to ensure protocol compatibility and long-term availability.

[Documentation →](https://github.com/iHost-Open-Source-Project/hassio-ihost-addon/blob/master/hassio-ihost-matter-bridge-addon/README.md)

---

### ESPHome Device Builder

This repository provides **custom-built ESPHome add-ons and container images for armv7** which are no longer supported by the official ESPHome distribution.

We only maintain compatibility and build infrastructure for the **32-bit architecture**.
If you encounter issues **unrelated to platform architecture** (such as ESPHome core features, YAML configuration, or device support), please report them to the [official ESPHome repository](https://github.com/esphome/esphome).

[Documentation →](https://github.com/iHost-Open-Source-Project/hassio-ihost-addon/tree/master/hassio-ihost-esphome)

---
### eWeLink-Remote Gateway

eWeLink-Remote Gateway add-on is an eWeLink-Remote Gateway gateway that supports adding eWeLink-Remote sub-devices and syncing sub-devices  to Home Assistant,such as **[R5](https://sonoff.tech/product/smart-wall-switches/r5/),[R5W](https://sonoff.tech/product/smart-wall-switches/r5/),[S-Mate](https://sonoff.tech/product/diy-smart-switches/s-mate/),[S-Mate2](https://sonoff.tech/product/diy-smart-switches/s-mate/)**. You can select eWeLink-Remote sub-devices in Home Assistant Automations and trigger automations through single-click,double-click,and long-press events reported by eWeLink-Remote Gateway sub-devices.

[Documentation →](https://github.com/iHost-Open-Source-Project/hassio-ihost-addon/tree/master/hassio-ihost-ewelink-remote)

---
### Matter Server

This repository provides **custom-built Matter Server add-ons and container images for armv7** which are not supported by the official Matter Server distribution.

Matter Python WebSocket Server for Home Assistant Core. Matter (formerly
known as Connected Home over IP or CHIP) is an IPv6 based smart home
standard. This add-on provides a Matter Controller which allows you to
commission and control of Matter devices. The matching Home Assistant Core
integration communicates via WebSocket with this server.

[Documentation →](https://github.com/iHost-Open-Source-Project/hassio-ihost-addon/tree/master/hassio-ihost-matter-server)

---


## License

All add-ons in this repository are released under the [MIT License](./LICENSE).

Some files in this project (located in `hassio-ihost-silabs-multiprotocol`) are based on code licensed under the Apache License 2.0. See the LICENSE file for more information.

---

## Maintainers

Maintained by the [iHost Open Source Project](https://github.com/iHost-Open-Source-Project).
