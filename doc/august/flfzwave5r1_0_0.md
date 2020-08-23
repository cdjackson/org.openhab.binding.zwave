---
layout: documentation
title: FLF-ZWAVE5 R1 - ZWave
---

{% include base.html %}

# FLF-ZWAVE5 R1 Z-Wave Wireless Flood/Freeze Sensor
This describes the Z-Wave device *FLF-ZWAVE5 R1*, manufactured by *Ecolink* with the thing type UID of ```Ecolink_flfzwave5r1_00_000```.

The device is in the category of *Sensor*, defining Device used to measure something.

![FLF-ZWAVE5 R1 product image](https://opensmarthouse.org/assets/zwave/attachments/744/ZWAVE5.png)


The FLF-ZWAVE5 R1 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

The FLF-ZWAVE5 R1 does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. Refer to the *Wakeup Information* section below for further information.

## Overview

  * Z-Wave+™ enabled device which detects flood and freeze.
  * Reports tamper condition when cover is open

### Inclusion Information

  1. Remove the battery for at least 10 seconds
  2. Reinstall the battery

### Exclusion Information

  1. Remove the battery for at least 10 seconds
  2. Reinstall the battery

### Wakeup Information

The FLF-ZWAVE5 R1 does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. The wakeup period can be configured in the user interface - it is advisable not to make this too short as it will impact battery life - a reasonable compromise is 1 hour.

The wakeup period does not impact the devices ability to report events or sensor data. The device can be manually woken with a button press on the device as described below - note that triggering a device to send an event is not the same as a wakeup notification, and this will not allow the controller to communicate with the device.


Not provided

## Channels

The following table summarises the channels available for the FLF-ZWAVE5 R1 -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Binary Sensor | sensor_binary | sensor_binary |  |  | 
| Alarm (burglar) | alarm_burglar | alarm_burglar |  |  | 
| Alarm (flood) | alarm_flood | alarm_flood |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |

### Binary Sensor
Channel type information on this channel is not found.

### Alarm (burglar)
Channel type information on this channel is not found.

### Alarm (flood)
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.



## Device Configuration

The device has no configuration parameters defined.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The FLF-ZWAVE5 R1 supports 1 association group.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.
Group one is a lifeline group who will receive unsolicited messages relating to flood/freeze notifications, case tampering notifications, low-battery notifications.

Association group 1 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_BINARY_V2| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V2| |
| COMMAND_CLASS_ALARM_V5| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V2| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_WAKE_UP_V2| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |

### Documentation Links

* [Conformance statement](https://www.opensmarthouse.org/zwavedatabase/744/pics.pdf)
* [Partial info from user guide](https://www.opensmarthouse.org/zwavedatabase/744/ecolink-data.pdf)
* [User Manual](https://www.opensmarthouse.org/zwavedatabase/744/Z-Wave-Plus-Wireless-Flood-Sensor-with-a-Probe-FLF-ZWAVE5-V5.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/744).
