---
layout: documentation
title: ARZ Solar - ZWave
---

{% include base.html %}

# ARZ Solar Roller Shutter
This describes the Z-Wave device *ARZ Solar*, manufactured by *Fakro* with the thing type UID of ```Fakro_arzsolar_00_000```.

The device is in the category of *Blinds*, defining Roller shutters, window blinds, etc..

![ARZ Solar product image](https://opensmarthouse.org/assets/zwave/attachments/853/arz-solar.jpg)


The ARZ Solar supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

## Overview

Roller shutter controlled by a remote control. Solar roller shutter is equipped with a control unit and accumulator. The accumulator is powered by a solar cell placed on the roller shutter. Recommended for places with no access to 230V supply.

### Inclusion Information

Start INCLUDE procedure with the controller of existing network and then press programming button P on the roller shutter being added to the network.

### Exclusion Information

Start EXCLUDE procedure with the controller of existing network and then press programming button P on the roller shutter being added to the network.

## Channels

The following table summarises the channels available for the ARZ Solar -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Dimmer | switch_dimmer | switch_dimmer |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |

### Switch
Channel type information on this channel is not found.

### Dimmer
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.



## Device Configuration

The device has no configuration parameters defined.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The device does not support associations.
## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| |
| COMMAND_CLASS_SWITCH_ALL_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_VERSION_V1| |

### Documentation Links

* [PDF manual](https://www.opensmarthouse.org/zwavedatabase/853/ARZ-SOLAR-FAKRO-EN.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/853).
