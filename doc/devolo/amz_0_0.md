---
layout: documentation
title: AMZ - ZWave
---

{% include base.html %}

# AMZ Awning Blinds Controller
This describes the Z-Wave device *AMZ*, manufactured by *Fakro* with the thing type UID of ```Fakro_amz_00_000```.

The device is in the category of *Blinds*, defining Roller shutters, window blinds, etc..

![AMZ product image](https://opensmarthouse.org/assets/zwave/attachments/616/amz.png)


The AMZ supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

Only for external installation with Fakro roof windows.

### Inclusion Information

  1. Press the "In/Ex" button on the controller.
  2. Press the programming button on the awning blind for 1 second.

### Exclusion Information

  1. Press the "In/Ex" button on the controller.
  2. Press the programming button on the awning blind for 1 second.

## Channels

The following table summarises the channels available for the AMZ -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Blinds control | blinds_control | blinds_control |  |  | 

### Switch
Channel type information on this channel is not found.

### Blinds control
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
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_VERSION_V1| |

### Documentation Links

* [User Manual](https://www.opensmarthouse.org/zwavedatabase/616/AMZ-Z-WAVE-FAKRO-EN.pdf)
* [User Manual](https://www.opensmarthouse.org/zwavedatabase/616/AMZ-Z-WAVE-FAKRO-EN.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/616).
