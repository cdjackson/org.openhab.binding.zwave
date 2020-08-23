---
layout: documentation
title: Series switch 0300/9498 - ZWave
---

{% include base.html %}

# Series switch 0300/9498 Series ON/OFF Switch Relay
This describes the Z-Wave device *Series switch 0300/9498*, manufactured by *Technisat* with the thing type UID of ```Technisat_seriesswitch_00_000```.

The device is in the category of *Wall Switch*, defining Any device attached to the wall that controls a binary status of something, for ex. a light switch.

![Series switch 0300/9498 product image](https://opensmarthouse.org/assets/zwave/attachments/1273/2020-07-17-13-33-05-TechniSat--Series-switch--300-9498----Series-.png)


The Series switch 0300/9498 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

The TechniSat series switch lets you operate two ceiling lamps in a smart home system controlled by Z-Wave, for example. At the same time, the switch itself can still be switched on and off manually. 

What's more, you can determine how much electricity you use and the switch can be integrated into complex schemes in smart home systems. So it's perfect for providing more home comfort.

### Inclusion Information

  1. Install the TechniSat Wall Switch.
  2. After checking the correct installation, re-enable electrical power at the main fuse or circuit breaker.
  3. Start the Z-Wave device add mode on your Z-Wave gateway, according to the gateway‘s manual.
  4. Press T1 3x within 1 second.
  5. The red status LED is on while the device is added to the Z-Wave network.
  6. The green LED is on for 5 seconds after successfully adding the device.

### Exclusion Information

Press and hold the upper position of the left button (T1) for at least 10 seconds when the shutter is in the top position.

## Channels

The following table summarises the channels available for the Series switch 0300/9498 -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Electric meter (watts) | meter_watts | meter_watts |  |  | 
| Electric meter (kWh) | meter_kwh | meter_kwh |  |  | 
| Scene Number | scene_number | scene_number |  |  | 
| Alarm (power) | alarm_power | alarm_power |  |  | 
| Switch 1 | switch_binary1 | switch_binary |  |  | 
| Electric meter (watts) 1 | meter_watts1 | meter_watts |  |  | 
| Electric meter (kWh) 1 | meter_kwh1 | meter_kwh |  |  | 
| Alarm (power) 1 | alarm_power1 | alarm_power |  |  | 
| Switch 2 | switch_binary2 | switch_binary |  |  | 
| Electric meter (watts) 2 | meter_watts2 | meter_watts |  |  | 
| Electric meter (kWh) 2 | meter_kwh2 | meter_kwh |  |  | 
| Alarm (power) 2 | alarm_power2 | alarm_power |  |  | 

### Switch
Channel type information on this channel is not found.

### Electric meter (watts)
Channel type information on this channel is not found.

### Electric meter (kWh)
Channel type information on this channel is not found.

### Scene Number
Channel type information on this channel is not found.

### Alarm (power)
Channel type information on this channel is not found.

### Switch 1
Channel type information on this channel is not found.

### Electric meter (watts) 1
Channel type information on this channel is not found.

### Electric meter (kWh) 1
Channel type information on this channel is not found.

### Alarm (power) 1
Channel type information on this channel is not found.

### Switch 2
Channel type information on this channel is not found.

### Electric meter (watts) 2
Channel type information on this channel is not found.

### Electric meter (kWh) 2
Channel type information on this channel is not found.

### Alarm (power) 2
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 3 configuration parameters available in the Series switch 0300/9498.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Central Scene notifications | Enable/Disable Central scene notifications for 2x-5x press |
| 2 | Current wattage meter | Interval of current wattage meter reports in 10 seconds |
| 3 | Active energy meter | Interval of active energy meter reports in minutes |

### Parameter 1: Central Scene notifications

Enable/Disable Central scene notifications for 2x-5x press

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Disable |
| 1 | Enable |

The manufacturer defined default value is ```1``` (Enable).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 2: Current wattage meter

Interval of current wattage meter reports in 10 seconds
**** - disable unsolicited reports

**3 ... 8640** (30 seconds - 1 day)
Values in the range 0 to 8640 may be set.

The manufacturer defined default value is ```3```.

This parameter has the configuration ID ```config_2_2``` and is of type ```INTEGER```.


### Parameter 3: Active energy meter

Interval of active energy meter reports in minutes
**** - disable unsolicited reports

**10 ... 30240** (10 minutes - 3 weeks)
Values in the range 0 to 30240 may be set.

The manufacturer defined default value is ```60```.

This parameter has the configuration ID ```config_3_2``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The Series switch 0300/9498 supports 3 association groups.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.
  * Device Reset Locally Notification
  * Central Scene notification
  * Meter Report
  * Switch Binary Report
  * Notification Report

Association group 1 supports 1 node.

### Group 2: Switch State 1

  * Basic Set

Association group 2 supports 10 nodes.

### Group 3: Switch State 2

  * Basic Set

Association group 3 supports 10 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_METER_V3| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V3| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_MULTI_CHANNEL_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V8| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_FIRMWARE_UPDATE_MD_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 1

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_METER_V3| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ALARM_V8| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 2

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_METER_V3| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ALARM_V8| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |

### Documentation Links

* [data sheet](https://www.opensmarthouse.org/zwavedatabase/1273/Technical-Data-Sheet-Series-switch-flush-mount-BJ.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/1273).
