---
layout: documentation
title: HS1DS - ZWave
---

{% include base.html %}

# HS1DS Window / Door Sensor
This describes the Z-Wave device *HS1DS*, manufactured by *Z-Wave.Me* with the thing type UID of ```Z-Wave.Me_hs1ds_00_000```.

The device is in the category of *Window*, defining Window.

![HS1DS product image](https://opensmarthouse.org/assets/zwave/attachments/783/hs1ds.png)


## Overview

This is a intelligent door sensor , adopts super low power Z-Wave wireless networking technology, makes a longer battery life-span, Feel open or close state of the door or window through the near and separation between sensor and magnetic. Dual sensor design, makes the installation more flexible and adaptable. Products are suitable for home, villas, factories, shops, warehouses, office buildings, banks, room and other places of safety prevention

### Inclusion Information

 press the device networking hole for 3 times in 1.5 seconds, then the green LED flashes quickly

### Exclusion Information

Not provided

## Channels

The following table summarises the channels available for the HS1DS -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Binary Sensor | sensor_door | sensor_door |  |  | 
| Alarm (burglar) | alarm_burglar | alarm_burglar |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |

### Binary Sensor
Channel type information on this channel is not found.

### Alarm (burglar)
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.



## Device Configuration

The device has no configuration parameters defined.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The HS1DS supports 1 association group.

### Group 1: Controller Updates


Association group 1 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_SENSOR_BINARY_V2| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ALARM_V4| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_WAKE_UP_V2| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |

### Documentation Links

* [Manual](https://www.opensmarthouse.org/zwavedatabase/783/HSIDS-Z.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/783).
