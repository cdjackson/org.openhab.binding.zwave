---
layout: documentation
title: Keyless Connected Smart Door Lock - ZWave
---

{% include base.html %}

# Keyless Connected Smart Door Lock Smart door lock with z-wave module.
This describes the Z-Wave device *Keyless Connected Smart Door Lock*, manufactured by *ASSA ABLOY* with the thing type UID of ```ASSA ABLOY_keylesslock_00_000```.

The device is in the category of *Lock*, defining Devices whose primary pupose is locking something.

![Keyless Connected Smart Door Lock product image](https://opensmarthouse.org/assets/zwave/attachments/948/Keyless-Finishes-v2.jpg)


The Keyless Connected Smart Door Lock supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

## Overview

The Yale Keyless Connected Smart Door Lock can have Z-Wave® and Yale modules added to allow easy integration to smart home systems.

### Inclusion Information

For more information on how to connect your smart door lock to a Yale system go to www.yale.co.uk/YaleEcoSystem. For other home automation systems please follow their instructions on adding a lock and when prompted follow the instructions below.

Touch the keypad with the palm of your hand. Enter the master code, followed by # key. Press the [4] button followed by # key. Press the [1] button followed by the # key. Please wait up to 60 seconds.

### Exclusion Information

For security reasons a lock will not connect to a new home automation system if it is linked to another. If you have changed your home automation system please remove the device from the old system before adding it on to the new one.

Touch the keypad with the palm of your hand. Enter the master code, followed by # key. Press the [4] button followed by # key. Press the [3] button followed by the # key. Please wait up to 60 seconds.

## Channels

The following table summarises the channels available for the Keyless Connected Smart Door Lock -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Door Lock | lock_door | lock_door |  |  | 
| Alarm (general) | alarm_general | alarm_general |  |  | 
| Alarm (access) | alarm_access | alarm_access |  |  | 
| Alarm (power) | alarm_power | alarm_power |  |  | 
| Alarm (raw) | alarm_raw | alarm_raw |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |
| Clock Time Offset | time_offset | time_offset |  |  | 

### Door Lock
Channel type information on this channel is not found.

### Alarm (general)
Channel type information on this channel is not found.

### Alarm (access)
Channel type information on this channel is not found.

### Alarm (power)
Channel type information on this channel is not found.

### Alarm (raw)
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.

### Clock Time Offset
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 4 configuration parameters available in the Keyless Connected Smart Door Lock.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Audio Volume | Sets the volume level of the beeps and voice prompts |
| 2 | Auto Re-lock | When enabled, the unit will automatically re-lock |
| 3 | Re-lock Time | Time after unlocking that the device will lock |
| 4 | Wrong Code Entry Limit | The number of invalid tries before the lock shutdowns and sends an alarm |
|  | Lock Timeout | Sets the time after which the door will auto lock |

### Parameter 1: Audio Volume

Sets the volume level of the beeps and voice prompts
1 = Silent 2 = Low 3 = High
The following option values may be configured, in addition to values in the range 1 to 3 -:

| Value  | Description |
|--------|-------------|
| 1 | Silent |
| 2 | Low |
| 3 | High |

The manufacturer defined default value is ```3``` (High).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 2: Auto Re-lock

When enabled, the unit will automatically re-lock
0 = Off 255 = On
The following option values may be configured, in addition to values in the range 0 to 255 -:

| Value  | Description |
|--------|-------------|
| 255 | On |

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_2_1``` and is of type ```INTEGER```.


### Parameter 3: Re-lock Time

Time after unlocking that the device will lock

Values in the range 7 to 90 may be set.

The manufacturer defined default value is ```7```.

This parameter has the configuration ID ```config_3_1``` and is of type ```INTEGER```.


### Parameter 4: Wrong Code Entry Limit

The number of invalid tries before the lock shutdowns and sends an alarm

Values in the range 1 to 7 may be set.

The manufacturer defined default value is ```3```.

This parameter has the configuration ID ```config_4_1``` and is of type ```INTEGER```.

### Lock Timeout

Sets the time after which the door will auto lock.

This parameter has the configuration ID ```doorlock_timeout``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The Keyless Connected Smart Door Lock supports 1 association group.

### Group 1: Alarm Reports

Alarm reports are sent out to all devices in the association group

Association group 1 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_DOOR_LOCK_LOGGING_V1| |
| COMMAND_CLASS_SCHEDULE_ENTRY_LOCK_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_DOOR_LOCK_V1| |
| COMMAND_CLASS_USER_CODE_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |
| COMMAND_CLASS_TIME_V1| |
| COMMAND_CLASS_TIME_PARAMETERS_V1| |
| COMMAND_CLASS_SECURITY_V1| |

### Documentation Links

* [Lock Manual](https://www.opensmarthouse.org/zwavedatabase/948/YSL-Keyless-Manual-2018-1B.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/948).
