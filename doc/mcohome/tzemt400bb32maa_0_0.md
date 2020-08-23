---
layout: documentation
title: TZEMT400BB32MAA - ZWave
---

{% include base.html %}

# TZEMT400BB32MAA Trane Z-Wave Programmable Thermostat
This describes the Z-Wave device *TZEMT400BB32MAA*, manufactured by *Trane Corporation* with the thing type UID of ```Trane Corporation_tzemt400bb32maa_00_000```.

The device is in the category of *HVAC*, defining Air condition devices, Fans.

![TZEMT400BB32MAA product image](https://opensmarthouse.org/assets/zwave/attachments/245/TZEMT400BB3.jpg)


The TZEMT400BB32MAA supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

Thermostat for Heating and Cooling HVAC System control

### Inclusion Information

  * Press the MENU button on the thermostat.
  * Scroll down to Z Wave Install, and press the Select button.
  * Press the Yes button to enroll the thermostat.

### Exclusion Information

  * Press the MENU button on the thermostat.
  * Scroll down to Z Wave Install, and press the Select button.
  * Press the Yes button to enroll the thermostat.

## Channels

The following table summarises the channels available for the TZEMT400BB32MAA -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Sensor (temperature) | sensor_temperature | sensor_temperature |  |  | 
| Thermostat mode | thermostat_mode | thermostat_mode |  |  | 
| Operating State | thermostat_state | thermostat_state |  |  | 
| Setpoint (heating) | thermostat_setpoint | thermostat_setpoint |  |  | 
| Setpoint (cooling) | thermostat_setpoint | thermostat_setpoint |  |  | 
| Thermostat fan mode | thermostat_fanmode | thermostat_fanmode |  |  | 
| Thermostat fan state | thermostat_fanstate | thermostat_fanstate |  |  | 
| Schedule Mode | config_decimal | config_decimal |  |  | 
| Clock Time Offset | time_offset | time_offset |  |  | 

### Sensor (temperature)
Channel type information on this channel is not found.

### Thermostat mode
Channel type information on this channel is not found.

### Operating State
Channel type information on this channel is not found.

### Setpoint (heating)
Channel type information on this channel is not found.

### Setpoint (cooling)
Channel type information on this channel is not found.

### Thermostat fan mode
Channel type information on this channel is not found.

### Thermostat fan state
Channel type information on this channel is not found.

### Schedule Mode
Send 0 to Hold and 1 to Run Schedule.

Channel type information on this channel is not found.

### Clock Time Offset
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 1 configuration parameters available in the TZEMT400BB32MAA.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 132 | Schedule Mode |  |

### Parameter 132: Schedule Mode



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Hold |
| 1 | Schedule |

The manufacturer defined default value is ```0``` (Hold).

This parameter has the configuration ID ```config_132_1``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The TZEMT400BB32MAA supports 1 association group.

### Group 1: Reports


Association group 1 supports 1 node.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V1| |
| COMMAND_CLASS_THERMOSTAT_MODE_V1| |
| COMMAND_CLASS_THERMOSTAT_OPERATING_STATE_V1| |
| COMMAND_CLASS_THERMOSTAT_SETPOINT_V1| |
| COMMAND_CLASS_THERMOSTAT_FAN_MODE_V1| |
| COMMAND_CLASS_THERMOSTAT_FAN_STATE_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_LOCK_V1| |
| COMMAND_CLASS_CLOCK_V1| |
| COMMAND_CLASS_ASSOCIATION_V1| |
| COMMAND_CLASS_VERSION_V1| |

### Documentation Links

* [User Manual](https://www.opensmarthouse.org/zwavedatabase/245/d3f32301-3cd0-496f-925a-a0d76971e67c.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/245).
