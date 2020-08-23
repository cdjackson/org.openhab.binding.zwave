---
layout: documentation
title: ZMNKAD - ZWave
---

{% include base.html %}

# ZMNKAD Qubino Luxy Smart Switch
This describes the Z-Wave device *ZMNKAD*, manufactured by *[Goap](http://www.qubino.com/)* with the thing type UID of ```Goap_luxyswitch_00_000```.

The device is in the category of *Wall Switch*, defining Any device attached to the wall that controls a binary status of something, for ex. a light switch.

![ZMNKAD product image](https://opensmarthouse.org/assets/zwave/attachments/1196/LuxySwitch-ProductImage-ZMNKAD.jpeg)


The ZMNKAD supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

The Qubino LUXY Smart Switch is ideal for gentle illumination of any room, for visual and sound notifications, and for controlling various loads, using the built-in relay.

### Inclusion Information

Manual inclusion is triggered by the following procedure: 

  * Full white needs to be active (c-button 2). The user can select it by quickly pressing the c-button2 once.
  * When full white is enabled, press c-button3 and hold it for 5 seconds (while white is glowing, hold c-button3 for 5 seconds).
  * After 5 seconds, the device starts flashing, with the following pattern: green 1 second on, 0.5 second off.
  * Once the device receives a nodeId or after 10 seconds, it stops flashing and turns green. 

### Exclusion Information

Exclusion is triggered by the following procedure:

  * Full white needs to be active (c-button 2).
  * When full white is enabled, press c-button3 and hold it for 5 seconds (while white is glowing hold c-button3 for 5 seconds).
  * After 5 seconds, the device starts flashing with the following pattern: red 1 second on, 0.5 second off. 
  * Once the device loses its nodeId or after 10 seconds, it stops flashing and turns red. 

## Channels

The following table summarises the channels available for the ZMNKAD -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Dimmer | switch_dimmer | switch_dimmer |  |  | 
| Electric meter (watts) | meter_watts | meter_watts |  |  | 
| Electric meter (kWh) | meter_kwh | meter_kwh |  |  | 
| Color Control | color_color | color_color |  |  | 
| Color Temperature | color_temperature | color_temperature |  |  | 
| Alarm (power) | alarm_power | alarm_power |  |  | 
| Alarm (SIREN) 0 | notification_siren | notification_siren |  |  | 
| Switch 1 | switch_binary1 | switch_binary |  |  | 
| Dimmer 1 | switch_dimmer1 | switch_dimmer |  |  | 
| Electric meter (watts) 1 | meter_watts1 | meter_watts |  |  | 
| Electric meter (kWh) 1 | meter_kwh1 | meter_kwh |  |  | 
| Color Control 1 | color_color1 | color_color |  |  | 
| Color Temperature 1 | color_temperature1 | color_temperature |  |  | 
| Alarm (SIREN) 1 | notification_siren1 | notification_siren |  |  | 
| Switch 2 | switch_binary2 | switch_binary |  |  | 
| Electric meter (watts) 2 | meter_watts2 | meter_watts |  |  | 
| Electric meter (kWh) 2 | meter_kwh2 | meter_kwh |  |  | 
| Alarm (power) 2 | alarm_power2 | alarm_power |  |  | 

### Switch
Channel type information on this channel is not found.

### Dimmer
Channel type information on this channel is not found.

### Electric meter (watts)
Channel type information on this channel is not found.

### Electric meter (kWh)
Channel type information on this channel is not found.

### Color Control
Channel type information on this channel is not found.

### Color Temperature
Channel type information on this channel is not found.

### Alarm (power)
Channel type information on this channel is not found.

### Alarm (SIREN) 0
Channel type information on this channel is not found.

### Switch 1
Channel type information on this channel is not found.

### Dimmer 1
Channel type information on this channel is not found.

### Electric meter (watts) 1
Channel type information on this channel is not found.

### Electric meter (kWh) 1
Channel type information on this channel is not found.

### Color Control 1
Channel type information on this channel is not found.

### Color Temperature 1
Channel type information on this channel is not found.

### Alarm (SIREN) 1
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

The following table provides a summary of the 11 configuration parameters available in the ZMNKAD.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Relay contact type | Relay contact type |
| 3 | Turning off alarming | Turning off alarming |
| 10 | Auto On timer | Auto On timer |
| 11 | Auto Off timer | Auto Off timer |
| 12 | Auto On timer relay | Auto On timer relay |
| 13 | Auto Off timer relay | Auto Off timer relay |
| 30 | Restore state on power failure | Restore state on power failure |
| 31 | Restore relay state on power failure | Restore relay state on power failure |
| 40 | Power Consumption Reporting Threshold | Power Consumption Reporting Threshold |
| 42 | Power Consumption Threshold (time) | Power Consumption Threshold (time) |
| 70 | Overload safety switch | Overload safety switch |

### Parameter 1: Relay contact type

Relay contact type

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | NO |
| 1 | NC |

The manufacturer defined default value is ```0``` (NO ).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 3: Turning off alarming

Turning off alarming
Default value 1

0 – only by z-wave command (basic set, switch multilevel set, switch multilevel start/stop level change, sound switch play tone, sound switch configuration, switch color set, switch color start/stop level change, notification report idle)

1 – capacitive input or z-wave command (basic set, switch multilevel set, switch multilevel start/stop level change, sound switch play tone, sound switch configuration, switch color set, switch color start/stop level change, notification report idle)
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Only by Z-Wave |
| 1 | Capacitive input or by Z-wave |

The manufacturer defined default value is ```1``` (Capacitive input or by Z-wave).

This parameter has the configuration ID ```config_3_1``` and is of type ```INTEGER```.


### Parameter 10: Auto On timer

Auto On timer
Defines the time after which the device is turned to last known state.

Default value 0

0 – disabled

30 – 32535 = 30 – 32535 seconds after which the device turns on
Values in the range 0 to 32535 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_10_2``` and is of type ```INTEGER```.


### Parameter 11: Auto Off timer

Auto Off timer
Defines the time after which the device is turned off.

Default value 0

0 – disabled

30 – 32535 = 30 – 32535 seconds after which the device turns off
Values in the range 0 to 32535 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_11_2``` and is of type ```INTEGER```.


### Parameter 12: Auto On timer relay

Auto On timer relay
Defines the time after which the device's relay is turned to last known state.

Default value 0

0 – disabled

30 – 32535 = 30  – 32535 seconds after which the device turns on
Values in the range 0 to 32535 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_12_2``` and is of type ```INTEGER```.


### Parameter 13: Auto Off timer relay

Auto Off timer relay
Defines the time after which the device's relay is turned off.

Default value 0

0 – disabled

30 – 32535 = 30 – 32535 seconds after which the device turns off
Values in the range 0 to 32535 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_13_2``` and is of type ```INTEGER```.


### Parameter 30: Restore state on power failure

Restore state on power failure
Default value 1

1 – enabled (the device will restore state on power failure)

0 – dissabled (the device will not restore state on power failure and will remain off)
Values in the range 0 to 1 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_30_1``` and is of type ```INTEGER```.


### Parameter 31: Restore relay state on power failure

Restore relay state on power failure
Default value 1

1 – enabled (the device will restore state on power failure)

0 – disabled (the device will not restore state on power failure and will remain off)
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Disabled |
| 1 | Enabled |

The manufacturer defined default value is ```1``` (Enabled).

This parameter has the configuration ID ```config_31_1``` and is of type ```INTEGER```.


### Parameter 40: Power Consumption Reporting Threshold

Power Consumption Reporting Threshold
Choose by how much power consumption needs to increase or decrease to be reported. Values correspond to percentages so if 10 is set (by default), the device will report any power consumption changes of 10% or more compared to the last reading.

Values (size is 1 byte dec):

default value 10

0 - Power consumption reporting disabled

1 - 100 = 1% - 100% Power consumption reporting enabled. New value is reported only when Wattage in real time changes by more than the percentage value set in this parameter compared to the previous Wattage reading, starting at 1% (the lowest value possible).

NOTE: Power consumption needs to increase or decrease by at least 1 Watt to be reported, REGARDLESS of percentage set in this parameter.
Values in the range 0 to 100 may be set.

The manufacturer defined default value is ```10```.

This parameter has the configuration ID ```config_40_1``` and is of type ```INTEGER```.


### Parameter 42: Power Consumption Threshold (time)

Power Consumption Threshold (time)
Set value refers to the time interval with which power consumption in Watts is reported (0 – 32535 seconds). If 300 is entered (by default), energy consumption reports will be sent to the gateway (hub) every 300 seconds (or 5 minutes).

default value 0

0 - Power consumption reporting disabled

30 - 32535 = 30 - 32535 seconds. Power consumption reporting enabled. Report is sent according to time interval (value) set here.
Values in the range 0 to 32535 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_42_2``` and is of type ```INTEGER```.


### Parameter 70: Overload safety switch

Overload safety switch
The function allows for turning off the controlled device in case of exceeding the defined power for more than 5s. Controlled device can be turned back on by input I1 or sending a control frame.

Values (size is 2 byte dec):

default value 2300

1 – 2300 = 1 W – 2300W

0 = function not active

ⓘ NOTE: This functionality is not an overload safety protection, please check the technical specifications chapter for more details.

In case of overload the following message will be send towards the controller:

COMMAND\_CLASS\_NOTIFICATION_V5

The Alarm V1 type field set to 0x00

Notification Type 0x08 and 0x08 (Overload detected)
Values in the range 0 to 2300 may be set.

The manufacturer defined default value is ```2300```.

This parameter has the configuration ID ```config_70_2``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The ZMNKAD supports 5 association groups.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.
Root endpoint
**Command Class/Command**

COMMAND\_CLASS\_DEVICE\_RESET\_LOCALLY, DEVICE\_RESET\_LOCALLY\_NOTIFICATION, COMMAND\_CLASS\_SWITCH\_MULTILEVEL\_V4, SWITCH\_MULTILEVEL\_REPORT\_V4, COMMAND\_CLASS\_SWITCH\_COLOR\_V3, SWITCH\_COLOR\_REPORT\_V3, COMMAND\_CLASS\_NOTIFICATION\_V8, NOTIFICATION\_REPORT\_V8, COMMAND\_CLASS\_SWITCH\_BINARY, SWITCH\_BINARY\_REPORT, COMMAND\_CLASS\_METER, METER\_REPORT

Association group 1 supports 1 node.

### Group 2: LEDs on/off

Root endpoint
**Command Class/Command**

COMMAND\_CLASS\_BASIC\_V2, BASIC\_SET_V2

Association group 2 supports 5 nodes.

### Group 3: Change of brightness

Root endpoint
**Command Class/Command**

COMMAND\_CLASS\_SWITCH\_MULTILEVEL\_V4, SWITCH\_MULTILEVEL\_SET_V4

Association group 3 supports 5 nodes.

### Group 4: Change of color

Root endpoint
**Command Class/Command**

COMMAND\_CLASS\_SWITCH\_COLOR\_V3, SWITCH\_COLOR\_SET_V3

Association group 4 supports 5 nodes.

### Group 5: Relay on/off

Root endpoint
**Command Class/Command**

COMMAND\_CLASS\_SWITCH\_MULTILEVEL\_V4, SWITCH\_MULTILEVEL\_SET_V4

Association group 5 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| Linked to BASIC|
| COMMAND_CLASS_METER_V3| |
| COMMAND_CLASS_SWITCH_COLOR_V3| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_MULTI_CHANNEL_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V8| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 1

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| Linked to BASIC|
| COMMAND_CLASS_METER_V3| |
| COMMAND_CLASS_SWITCH_COLOR_V3| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ALARM_V8| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
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
| COMMAND_CLASS_SECURITY_V1| |

### Documentation Links

* [Manual](https://www.opensmarthouse.org/zwavedatabase/1196/Qubino-Luxy-Smart-Light-extended-manual-eng.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/1196).
