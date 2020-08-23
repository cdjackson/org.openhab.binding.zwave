---
layout: documentation
title: EasyPlug - ZWave
---

{% include base.html %}

# EasyPlug Wall Plug
This describes the Z-Wave device *EasyPlug*, manufactured by *Wintop* with the thing type UID of ```Wintop_easyplug_00_000```.

The device is in the category of *Power Outlet*, defining Small devices to be plugged into a power socket in a wall which stick there.

![EasyPlug product image](https://opensmarthouse.org/assets/zwave/attachments/218/easyplug.png)


The EasyPlug supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

  * Power supply, home automation
  * Expansion to easy starter pack contains:
  * 1x EASYPlug surface-mounted dim adapter
  * Power supply accessory

### Inclusion Information

Press and hold the button on the front side of the device for 1 second (count 21).

### Exclusion Information

Not provided

## Channels

The following table summarises the channels available for the EasyPlug -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Sensor (temperature) | sensor_temperature | sensor_temperature |  |  | 
| Electric meter (kWh) | meter_kwh | meter_kwh |  |  | 
| Electric meter (watts) | meter_watts | meter_watts |  |  | 

### Switch
Channel type information on this channel is not found.

### Sensor (temperature)
Channel type information on this channel is not found.

### Electric meter (kWh)
Channel type information on this channel is not found.

### Electric meter (watts)
Channel type information on this channel is not found.



## Device Configuration

The device has no configuration parameters defined.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The EasyPlug supports 1 association group.

### Group 1: Group 1


Association group 1 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_SWITCH_ALL_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V1| |
| COMMAND_CLASS_METER_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_PROTECTION_V1| |
| COMMAND_CLASS_ASSOCIATION_V1| |
| COMMAND_CLASS_VERSION_V1| |

### Documentation Links

* [Manual Text](https://www.opensmarthouse.org/zwavedatabase/218/Easyplug-Manual.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/218).
