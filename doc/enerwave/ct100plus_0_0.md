---
layout: documentation
title: CT100 Plus - ZWave
---

{% include base.html %}

# CT100 Plus Z-Wave Thermostat
This describes the Z-Wave device *CT100 Plus*, manufactured by *Radio Thermostat Company of America (RTC)* with the thing type UID of ```Radio Thermostat Company of America (RTC)_ct100plus_00_000```.

The device is in the category of *HVAC*, defining Air condition devices, Fans.

![CT100 Plus product image](https://opensmarthouse.org/assets/zwave/attachments/641/ct100-plus.png)


The CT100 Plus supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

## Overview

The CT100 Plus is a sleek, modern thermostat design for home automation systems. It’s clean user interface compliments app-enabled systems. It features adjustable real-time alerts to enable cloud triggers, a robust data stream of HVAC information for cloud monitoring, and configurable comfort response settings to customize home control scenes. The CT100 Plus is compatible with all popular HVAC systems and is battery-operated without the need for a C-wire.

### Inclusion Information

  1.  From the CT100’s Menu screen, touch MATE under the radio icon. The Network Include screen displays a large r1.
  2. Touch MATE again. This initiates the network connection (mating) process. The MATE icon and the status indicator LEDs will blink.

When the CT100 has successfully joined a Z-Wave network, the MATE icon is replaced by the LINK icon under the radio tower. 

### Exclusion Information

  1.  From the CT100’s Menu screen, touch MATE under the radio icon. The Network Include screen displays a large r1.
  2. Touch MATE again. This initiates the network connection (mating) process. The MATE icon and the status indicator LEDs will blink.

When you are trying to disconnect from (leave) a network, the LINK icon disappears when the node has successfully left the network.

## Channels

The following table summarises the channels available for the CT100 Plus -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Binary Sensor | sensor_binary | sensor_binary |  |  | 
| Sensor (relative humidity) | sensor_relhumidity | sensor_relhumidity |  |  | 
| Sensor (temperature) | sensor_temperature | sensor_temperature |  |  | 
| Thermostat mode | thermostat_mode | thermostat_mode |  |  | 
| Operating State | thermostat_state | thermostat_state |  |  | 
| Setpoint (heating) | thermostat_setpoint | thermostat_setpoint |  |  | 
| Setpoint (cooling) | thermostat_setpoint | thermostat_setpoint |  |  | 
| Setpoint (dry air) | thermostat_setpoint | thermostat_setpoint |  |  | 
| Setpoint (furnace) | thermostat_setpoint | thermostat_setpoint |  |  | 
| Thermostat fan mode | thermostat_fanmode | thermostat_fanmode |  |  | 
| Thermostat fan state | thermostat_fanstate | thermostat_fanstate |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |
| Clock Time Offset | time_offset | time_offset |  |  | 
| Sensor (relative humidity) 1 | sensor_relhumidity1 | sensor_relhumidity |  |  | 
| Sensor (temperature) 1 | sensor_temperature1 | sensor_temperature |  |  | 
| Thermostat mode 1 | thermostat_mode1 | thermostat_mode |  |  | 
| Operating State 1 | thermostat_state1 | thermostat_state |  |  | 
| Setpoint (heating) 1 | thermostat_setpoint1 | thermostat_setpoint |  |  | 
| Setpoint (cooling) 1 | thermostat_setpoint1 | thermostat_setpoint |  |  | 
| Setpoint (dry air) 1 | thermostat_setpoint1 | thermostat_setpoint |  |  | 
| Setpoint (furnace) 1 | thermostat_setpoint1 | thermostat_setpoint |  |  | 
| Thermostat fan mode 1 | thermostat_fanmode1 | thermostat_fanmode |  |  | 
| Thermostat fan state 1 | thermostat_fanstate1 | thermostat_fanstate |  |  | 
| Clock Time Offset 1 | time_offset1 | time_offset |  |  | 
| Sensor (relative humidity) 2 | sensor_relhumidity2 | sensor_relhumidity |  |  | 
| Sensor (temperature) 2 | sensor_temperature2 | sensor_temperature |  |  | 

### Binary Sensor
Channel type information on this channel is not found.

### Sensor (relative humidity)
Channel type information on this channel is not found.

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

### Setpoint (dry air)
Channel type information on this channel is not found.

### Setpoint (furnace)
Channel type information on this channel is not found.

### Thermostat fan mode
Channel type information on this channel is not found.

### Thermostat fan state
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.

### Clock Time Offset
Channel type information on this channel is not found.

### Sensor (relative humidity) 1
Channel type information on this channel is not found.

### Sensor (temperature) 1
Channel type information on this channel is not found.

### Thermostat mode 1
Channel type information on this channel is not found.

### Operating State 1
Channel type information on this channel is not found.

### Setpoint (heating) 1
Channel type information on this channel is not found.

### Setpoint (cooling) 1
Channel type information on this channel is not found.

### Setpoint (dry air) 1
Channel type information on this channel is not found.

### Setpoint (furnace) 1
Channel type information on this channel is not found.

### Thermostat fan mode 1
Channel type information on this channel is not found.

### Thermostat fan state 1
Channel type information on this channel is not found.

### Clock Time Offset 1
Channel type information on this channel is not found.

### Sensor (relative humidity) 2
Channel type information on this channel is not found.

### Sensor (temperature) 2
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 12 configuration parameters available in the CT100 Plus.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Temperature Reporting Threshold | Reporting threshold for changes in the ambient temperature |
| 2 | HVAC Settings | Configured HVAC settings |
| 3 | Utility Lock Enable/Disable | Prevents setpoint changes at thermostat |
| 4 | Power Status | C-Wire / Battery Status |
| 5 | Humidity Reporting Threshold | Reporting threshold for changes in the relative humidity |
| 6 | Auxiliary/Emergency | Enables or disables auxiliary / emergency heating |
| 7 | Thermostat Swing Temperature | Variance allowed from setpoint to engage HVAC |
| 8 | Thermostat Diff Temperature | Configures additional stages |
| 9 | Thermostat Recovery Mode | Fast or Economy recovery mode |
| 10 | Temperature Reporting Filter | Upper/Lower bounds for thermostat temperature reporting |
| 11 | Simple UI Mode | Simple mode enable/disable |
| 12 | Multicast | Enable or disables Multicast |

### Parameter 1: Temperature Reporting Threshold

Reporting threshold for changes in the ambient temperature
This value determines the reporting threshold when association reporting is enabled. Unsupported values will be ignored.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Disabled |
| 1 | 0.5° F |
| 2 | 1.0° F |
| 3 | 1.5° F |
| 4 | 2.0° F |

The manufacturer defined default value is ```2``` (1.0° F).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 2: HVAC Settings

Configured HVAC settings
Byte 1 = HVAC Setup: Normal (0x01) or Heat Pump (0x02)  
Byte 2 = Aux Setup (Gas (0x01) or Electric (0x02)) & Number of Auxiliary Stages (Heat Pump)/Number of Heat Stages (Normal)  
Byte 3 = Number of Heat Pump Stages  
Byte 4 = Number of Cool Stages
Values in the range 0 to 0 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_2_4``` and is of type ```INTEGER```.
This is a read only parameter.


### Parameter 3: Utility Lock Enable/Disable

Prevents setpoint changes at thermostat
If set to 0, the utility lock is disabled, all other values, 1-255, will enable the utility lock. This will prevent changes to the setpoint at the thermostat screen.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Utility lock disabled |
| 1 | Utility lock enabled |

The manufacturer defined default value is ```0``` (Utility lock disabled).

This parameter has the configuration ID ```config_3_1_wo``` and is of type ```INTEGER```.
This is a write only parameter.


### Parameter 4: Power Status

C-Wire / Battery Status
If 0x01, the thermostat is powered by a C-wire. If 0x02, the thermostat is powered by batteries.
Values in the range 0 to 0 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_4_1``` and is of type ```INTEGER```.
This is a read only parameter.


### Parameter 5: Humidity Reporting Threshold

Reporting threshold for changes in the relative humidity
This value determines the reporting threshold when association reporting is enabled. Unsupported values will be ignored.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Disabled |
| 1 | 3% RH |
| 2 | 5% RH |
| 3 | 10% RH |

The manufacturer defined default value is ```0``` (Disabled).

This parameter has the configuration ID ```config_5_1``` and is of type ```INTEGER```.


### Parameter 6: Auxiliary/Emergency

Enables or disables auxiliary / emergency heating
If set to 0, auxiliary / emergency heat is disabled, all other values, 1-255, will enable the auxiliary / emergency heat. This can only be enabled when the thermostat is set to Heat Pump mode.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Auxiliary/Emergency heat disabled |
| 1 | Auxiliary/Emergency heat enabled |

The manufacturer defined default value is ```0``` (Auxiliary/Emergency heat disabled).

This parameter has the configuration ID ```config_6_1``` and is of type ```INTEGER```.


### Parameter 7: Thermostat Swing Temperature

Variance allowed from setpoint to engage HVAC
The thermostat swing temperature is in units of 0.5 degrees Fahrenheit.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 1 | 0.5° F |
| 2 | 1.0° F |
| 3 | 1.5° F |
| 4 | 2.0° F |
| 5 | 2.5° F |
| 6 | 3.0° F |
| 7 | 3.5° F |
| 8 | 4.0° F |

The manufacturer defined default value is ```2``` (1.0° F).

This parameter has the configuration ID ```config_7_1``` and is of type ```INTEGER```.


### Parameter 8: Thermostat Diff Temperature

Configures additional stages
Sets the differential temperature for multi-stage HVAC systems. The differential temperature delta defines when the thermostat will turn on additional stages. This command configures both the heat and cool differential temperatures.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 4 | 2.0° F |
| 8 | 4.0° F |
| 12 | 6.0° F |

The manufacturer defined default value is ```4``` (2.0° F).

This parameter has the configuration ID ```config_8_1``` and is of type ```INTEGER```.


### Parameter 9: Thermostat Recovery Mode

Fast or Economy recovery mode
The Thermostat Recovery Mode can be either fast (1) or economy (2).
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 1 | Fast recovery mode |
| 2 | Economy recovery mode |

The manufacturer defined default value is ```2``` (Economy recovery mode).

This parameter has the configuration ID ```config_9_1``` and is of type ```INTEGER```.


### Parameter 10: Temperature Reporting Filter

Upper/Lower bounds for thermostat temperature reporting
The thermostat will report ambient temperature changes for temperature values less than the lower bound. This field must be between 0F and 124F. By default, this value is 124F (report all temperature changes).
Values in the range 0 to 124 may be set.

The manufacturer defined default value is ```124```.

This parameter has the configuration ID ```config_10_4``` and is of type ```INTEGER```.


### Parameter 11: Simple UI Mode

Simple mode enable/disable
If the value is set to 0 then Normal Mode is enabled. If the value is set to 1 then Simple Mode is enabled.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Normal mode enabled |
| 1 | Simple mode enabled |

The manufacturer defined default value is ```1``` (Simple mode enabled).

This parameter has the configuration ID ```config_11_1``` and is of type ```INTEGER```.


### Parameter 12: Multicast

Enable or disables Multicast
If set to 0, Multicast is disabled. If set to 1, Multicast is enabled.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Multicast disabled |
| 1 | Multicast enabled |

The manufacturer defined default value is ```0``` (Multicast disabled).

This parameter has the configuration ID ```config_12_1``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The CT100 Plus supports 1 association group.

### Group 1: Group 1

Send report about Thermostat Mode, Thermostat Operating State, Fan Mode, Fan State, Setpoint, Sensor Multilevel

Association group 1 supports 2 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_BINARY_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V5| |
| COMMAND_CLASS_THERMOSTAT_MODE_V1| |
| COMMAND_CLASS_THERMOSTAT_OPERATING_STATE_V1| |
| COMMAND_CLASS_THERMOSTAT_SETPOINT_V1| |
| COMMAND_CLASS_THERMOSTAT_FAN_MODE_V1| |
| COMMAND_CLASS_THERMOSTAT_FAN_STATE_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ANTITHEFT_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_MULTI_CHANNEL_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_FIRMWARE_UPDATE_MD_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_CLOCK_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |
| COMMAND_CLASS_INDICATOR_V1| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 1

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V5| |
| COMMAND_CLASS_THERMOSTAT_MODE_V1| |
| COMMAND_CLASS_THERMOSTAT_OPERATING_STATE_V1| |
| COMMAND_CLASS_THERMOSTAT_SETPOINT_V1| |
| COMMAND_CLASS_THERMOSTAT_FAN_MODE_V1| |
| COMMAND_CLASS_THERMOSTAT_FAN_STATE_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_FIRMWARE_UPDATE_MD_V1| |
| COMMAND_CLASS_CLOCK_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_INDICATOR_V1| |
#### Endpoint 2

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V5| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |

### Documentation Links

* [CT100 Plus User Guide](https://www.opensmarthouse.org/zwavedatabase/641/CT100-Plus-UserGuide.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/641).
