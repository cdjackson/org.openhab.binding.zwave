---
layout: documentation
title: BTZEUMV1 - ZWave
---

{% include base.html %}

# BTZEUMV1 Danalock Universal Module V1
This describes the Z-Wave device *BTZEUMV1*, manufactured by *[Poly-control](https://www.danalock.com/)* with the thing type UID of ```Poly-control_btzeumv1_00_000```.

The device is in the category of *Lock*, defining Devices whose primary pupose is locking something.

![BTZEUMV1 product image](https://opensmarthouse.org/assets/zwave/attachments/868/danalock-universal-tueroeffner-60004.jpg)


The BTZEUMV1 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

## Overview

The universal module enables the control of existing electrical locking systems via smartphone. It is a circuit board with a relay to switch potential-free contacts. The module is connected near the lock system and actuates engine locks, garage doors, digital cylinders or the door number.

### Inclusion Information

To add or include the Danalock into a Z-Wave network

  1. Set the controller in inclusion mode
  2. Push the switch once until you hear two beeps.

### Exclusion Information

To remove or exclude the Danalock from a Z-Wave network

  1. Set the controller in inclusion mode
  2. Push the switch once until you hear two beeps.

## Channels

The following table summarises the channels available for the BTZEUMV1 -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Door Lock | lock_door | lock_door |  |  | 
| Alarm (access) | alarm_access | alarm_access |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |
| Clock Time Offset | time_offset | time_offset |  |  | 

### Door Lock
Channel type information on this channel is not found.

### Alarm (access)
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.

### Clock Time Offset
Channel type information on this channel is not found.



## Device Configuration

The device has no configuration parameters defined.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The BTZEUMV1 supports 1 association group.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.
Z-Wave Plus Lifeline

Association group 1 supports 1 node.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SCHEDULE_ENTRY_LOCK_V1| |
| COMMAND_CLASS_SCHEDULE_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_DOOR_LOCK_V1| |
| COMMAND_CLASS_USER_CODE_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V3| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_FIRMWARE_UPDATE_MD_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |
| COMMAND_CLASS_TIME_V1| |
| COMMAND_CLASS_TIME_PARAMETERS_V1| |
| COMMAND_CLASS_SECURITY_V1| |

### Documentation Links

* [Manual](https://www.opensmarthouse.org/zwavedatabase/868/danalock-universalmodul-v1.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/868).
