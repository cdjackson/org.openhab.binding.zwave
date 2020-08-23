---
layout: documentation
title: ARF - ZWave
---

{% include base.html %}

# ARF Roller blind module
This describes the Z-Wave device *ARF*, manufactured by *Fakro* with the thing type UID of ```Fakro_arf_00_000```.

The device is in the category of *Blinds*, defining Roller shutters, window blinds, etc..

![ARF product image](https://opensmarthouse.org/assets/zwave/attachments/848/arf-1.png)


The ARF supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

The ARF blackout blind is a stylish, decorative blind with runners at the sides to allow the blind to be posi tioned anywhere on the window. It also prevents daylight entering at the sides, thus providing a complete blackout. 

The ARF Z-Wave blackout blind has a built in 12V electric drive which enables operation at 12V blinds by remote control or wall switch. The standard version of the action blinds ARF Z-Wave is only possible with the window closed. 

### Inclusion Information

Start INCLUDE procedure with the controller of existing network and then press programming button P on the roller shutter being added to the network.

### Exclusion Information

Start EXCLUDE procedure with the controller of existing network and then press programming button P on the roller shutter being added to the network.

## Channels

The following table summarises the channels available for the ARF -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Blinds control | blinds_control | blinds_control |  |  | 
| Alarm (power) | alarm_power | alarm_power |  |  | 

### Switch
Channel type information on this channel is not found.

### Blinds control
Channel type information on this channel is not found.

### Alarm (power)
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
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| Linked to BASIC|
| COMMAND_CLASS_SWITCH_ALL_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V3| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_NODE_NAMING_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |

### Documentation Links

* [User Manual (EN)](https://www.opensmarthouse.org/zwavedatabase/848/ARF-ARP-Z-WAVE-EN.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/848).
