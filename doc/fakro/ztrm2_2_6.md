---
layout: documentation
title: Heatit Z-TRM 2 - ZWave
---

{% include base.html %}

# Heatit Z-TRM 2 Floor thermostat
This describes the Z-Wave device *Heatit Z-TRM 2*, manufactured by *ThermoFloor* with the thing type UID of ```ThermoFloor_ztrm2_02_006```.
This version of the device is limited to firmware version 2.6

The device is in the category of *HVAC*, defining Air condition devices, Fans.

![Heatit Z-TRM 2 product image](https://opensmarthouse.org/assets/zwave/attachments/854/ztrm2.JPG)


The Heatit Z-TRM 2 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

### FEATURES

  * Floor sensor
  * Built-in room sensor
  * External room sensor
  * Temperature limiter
  * Weekly program/setback via gateway or pilot wire
  * Multilevel sensor command class
  * Firmware updates (OTA)
  * Power metering
  * LED-diode
  * Can be used in connection with different NTC-sensors
  * Lock mode/child lock
  * Calibration
  * 8 associations
  * Supports encryption mode: S0, S2 Authenticated Class, S2 Unauthenticated Class

### Inclusion Information

To include the thermostat to your home automation gateway, press Center (confirm) for 10 seconds.

The display will show OFF. Press Right (down) 4 times till you see Con in the display.

Now start add device in your home automation software.

Start inclusion mode by pressing Center (confirm) for approximately 2 seconds.

Adding mode is indicated in the display by some 'circling' LED segments in the display until the timeout occurs after 20 seconds or the module has been added in the network.

Confirmation will show Inc in the display. If inclusion fails, Err (error) will appear.

Leave programming mode by choosing ESC in the menu.

Your thermostat is ready for use with default settings.

### Exclusion Information

To exclude the thermostat to your home automation gateway, press Center (confirm) for 10 seconds.

The display will show OFF. Press Right (down) 4 times till you see Con in the display.

Now start excluding device in your home automation software.

Start exclusion mode by pressing Center (confirm) for approximately 2 seconds.

Adding mode is indicated in the display by some 'circling' LED segments in the display until the timeout occurs after 20 seconds or the module has been excluded from the network.

Confirmation will show Ecl in the display. If exclusion fails, Err (error) will appear.

Leave programming mode by choosing ESC in the menu.

## Channels

The following table summarises the channels available for the Heatit Z-TRM 2 -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Electric meter (volts) | meter_voltage | meter_voltage |  |  | 
| Electric meter (watts) | meter_watts | meter_watts |  |  | 
| Electric meter (kWh) | meter_kwh | meter_kwh |  |  | 
| Thermostat mode | thermostat_mode | thermostat_mode |  |  | 
| Setpoint (furnace) | thermostat_setpoint | thermostat_setpoint |  |  | 
| Setpoint (heating) | thermostat_setpoint | thermostat_setpoint |  |  | 
| Setpoint (cooling) | thermostat_setpoint | thermostat_setpoint |  |  | 
| P Setting | config_decimal | config_decimal |  |  | 
| Display brightness | config_decimal | config_decimal |  |  | 
| Energy saving mode setpoint | config_decimal | config_decimal |  |  | 
| Switch 1 | switch_binary1 | switch_binary |  |  | 
| Electric meter (volts) 1 | meter_voltage1 | meter_voltage |  |  | 
| Electric meter (watts) 1 | meter_watts1 | meter_watts |  |  | 
| Electric meter (kWh) 1 | meter_kwh1 | meter_kwh |  |  | 
| External sensor | sensor_temperature2 | sensor_temperature |  |  | 
| Floor sensor | sensor_temperature3 | sensor_temperature |  |  | 
| Sensor (temperature) 4 | sensor_temperature4 | sensor_temperature |  |  | 

### Switch
Channel type information on this channel is not found.

### Electric meter (volts)
Channel type information on this channel is not found.

### Electric meter (watts)
Channel type information on this channel is not found.

### Electric meter (kWh)
Channel type information on this channel is not found.

### Thermostat mode
Channel type information on this channel is not found.

### Setpoint (furnace)
Channel type information on this channel is not found.

### Setpoint (heating)
Channel type information on this channel is not found.

### Setpoint (cooling)
Channel type information on this channel is not found.

### P Setting
Channel type information on this channel is not found.

### Display brightness
Channel type information on this channel is not found.

### Energy saving mode setpoint
Channel type information on this channel is not found.

### Switch 1
Channel type information on this channel is not found.

### Electric meter (volts) 1
Channel type information on this channel is not found.

### Electric meter (watts) 1
Channel type information on this channel is not found.

### Electric meter (kWh) 1
Channel type information on this channel is not found.

### External sensor
Channel type information on this channel is not found.

### Floor sensor
Channel type information on this channel is not found.

### Sensor (temperature) 4
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 25 configuration parameters available in the Heatit Z-TRM 2.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Operation mode | Operation mode |
| 2 | Sensor mode | Sensor mode |
| 3 | Floor sensor type | Floor sensor type |
| 4 | Temperature control hysteresis (DIFF I) | Temperature control hysteresis (DIFF I) |
| 5 | Floor minimum temperature limit (FLo) | Floor minimum temperature limit (FLo) |
| 6 | Floor maximum temperature (FHi) | Floor maximum temperature (FHi) |
| 7 | Air minimum temperature limit (ALo) | Air minimum temperature limit (ALo) |
| 8 | Air maximum temperature limit (AHi) | Air maximum temperature limit (AHi) |
| 9 | FP mode P setting (PLo) | FP mode P setting (PLo) |
| 10 | Heating mode setpoint (CO) | Heating mode setpoint (CO) |
| 11 | Energy saving mode setpoint (ECO) | Energy saving mode setpoint (ECO) |
| 12 | P setting | P setting |
| 13 | Cooling setpoint (COOL) | Cooling setpoint (COOL) |
| 14 | Room sensor calibration | Room sensor calibration |
| 15 | Floor sensor calibration | Floor sensor calibration |
| 16 | External sensor calibration | External sensor calibration |
| 17 | Temperature display | Temperature display |
| 18 | Button brightness - dimmed state | Button brightness - dimmed state |
| 19 | Button brightness - active state | Button brightness - active state |
| 20 | Display brightness - dimmed state | Display brightness - dimmed state |
| 21 | Display brightness - active state | Display brightness - active state |
| 22 | Temperature report interval | Temperature report interval |
| 23 | Temperature report hysteresis | Temperature report hysteresis |
| 24 | Meter report interval | Meter report interval |
| 25 | Meter report delta value | Meter report delta value |

### Parameter 1: Operation mode

Operation mode
Value = 0, Off (default)  
Value = 1, Heating mode  
Value = 2, Cooling mode (not implemented)  
Value = 11, Energy saving mode
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Off. (default) |
| 1 | Heating mode |
| 2 | Cooling mode (not implemented) |
| 11 | Energy saving heating mode |

The manufacturer defined default value is ```0``` (Off. (default)).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 2: Sensor mode

Sensor mode
Value = 0, F-mode, floor sensor mode  
Value = 1, A-mode, internal room sensor mode (default)  
Value = 2, AF-mode, internal sensor and floor sensor mode  
Value = 3, A2-mode, external room sensor mode  
Value = 4, P-mode, power regulator mode  
Value = 5, FP-mode, floor sensor and power regulator mode
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | F-mode, floor sensor mode |
| 1 | A-mode, internal room sensor mode (default) |
| 2 | AF-mode, internal sensor and floor sensor mode |
| 3 | A2-mode, external room sensor mode |
| 4 | P-mode, power regulator mode |
| 5 | FP-mode, floor sensor and power regulator mode |

The manufacturer defined default value is ```1``` (A-mode, internal room sensor mode (default)).

This parameter has the configuration ID ```config_2_1``` and is of type ```INTEGER```.


### Parameter 3: Floor sensor type

Floor sensor type
1. Value = 0, 10K-NTC (default)  
2. Value = 1, 12K-NTC  
3. Value = 2, 15K-NTC  
4. Value = 3, 22K-NTC  
5. Value = 4, 33K-NTC  
6. Value = 5, 47K-NTC
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | 10K-NTC (default) |
| 1 | 12K-NTC |
| 2 | 15K-NTC |
| 3 | 22K-NTC |
| 4 | 33K-NTC |
| 5 | 47K-NTC |

The manufacturer defined default value is ```0``` (10K-NTC (default)).

This parameter has the configuration ID ```config_3_1``` and is of type ```INTEGER```.


### Parameter 4: Temperature control hysteresis (DIFF I)

Temperature control hysteresis (DIFF I)
1. Value = 0 - 30, 0.3C - 3.0C (default is 0.5C)  
When using a water-based heating, the recommended hysteresis is a minimum of 1.0C
Values in the range 0 to 30 may be set.

The manufacturer defined default value is ```5```.

This parameter has the configuration ID ```config_4_1``` and is of type ```INTEGER```.


### Parameter 5: Floor minimum temperature limit (FLo)

Floor minimum temperature limit (FLo)
1. Value = 50 - 400, 5.0C - 40.0C, default = 5.0C
Values in the range 50 to 400 may be set.

The manufacturer defined default value is ```50```.

This parameter has the configuration ID ```config_5_2``` and is of type ```INTEGER```.


### Parameter 6: Floor maximum temperature (FHi)

Floor maximum temperature (FHi)
1. Value = 50 - 400, 5.0C - 40.0C, default = 40.0C)
Values in the range 50 to 400 may be set.

The manufacturer defined default value is ```400```.

This parameter has the configuration ID ```config_6_2``` and is of type ```INTEGER```.


### Parameter 7: Air minimum temperature limit (ALo)

Air minimum temperature limit (ALo)
1. Value = 50 - 400, 5.0C - 40.0C, default = 5.0C
Values in the range 50 to 400 may be set.

The manufacturer defined default value is ```50```.

This parameter has the configuration ID ```config_7_2``` and is of type ```INTEGER```.


### Parameter 8: Air maximum temperature limit (AHi)

Air maximum temperature limit (AHi)
1. Value = 50 - 400, 5.0C - 40.0C, default = 40.0C)
Values in the range 50 to 400 may be set.

The manufacturer defined default value is ```400```.

This parameter has the configuration ID ```config_8_2``` and is of type ```INTEGER```.


### Parameter 9: FP mode P setting (PLo)

FP mode P setting (PLo)
1. Value = 0 - 9, default = 0
Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_9_1``` and is of type ```INTEGER```.


### Parameter 10: Heating mode setpoint (CO)

Heating mode setpoint (CO)
1. Value = 50 - 400, 5.0C - 40.0C, default = 21.0C
Values in the range 50 to 400 may be set.

The manufacturer defined default value is ```210```.

This parameter has the configuration ID ```config_10_2``` and is of type ```INTEGER```.


### Parameter 11: Energy saving mode setpoint (ECO)

Energy saving mode setpoint (ECO)
1. Value = 50 - 400, 5.0C - 40.0C, default = 18.0C
Values in the range 50 to 400 may be set.

The manufacturer defined default value is ```180```.

This parameter has the configuration ID ```config_11_2``` and is of type ```INTEGER```.


### Parameter 12: P setting

P setting
1. Value = 0 - 10, default = 2
Values in the range 0 to 10 may be set.

The manufacturer defined default value is ```2```.

This parameter has the configuration ID ```config_12_1``` and is of type ```INTEGER```.


### Parameter 13: Cooling setpoint (COOL)

Cooling setpoint (COOL)
1. Value = 50 - 400, 5.0C - 40.0C, default = 21.0C
Values in the range 50 to 400 may be set.

The manufacturer defined default value is ```210```.

This parameter has the configuration ID ```config_13_2``` and is of type ```INTEGER```.


### Parameter 14: Room sensor calibration

Room sensor calibration
1. Value = -40 - 40, -4.0V - 4.0C, default = 0.0C
Values in the range -40 to 40 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_14_1``` and is of type ```INTEGER```.


### Parameter 15: Floor sensor calibration

Floor sensor calibration
1. Value = -40 - 40, -4.0C - 4.0C, default = 0.0C
Values in the range -40 to 40 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_15_1``` and is of type ```INTEGER```.


### Parameter 16: External sensor calibration

External sensor calibration
1. Value = -40 - 40, -4.0C - 4.0C, default = 0.0C
Values in the range -40 to 40 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_16_1``` and is of type ```INTEGER```.


### Parameter 17: Temperature display

Temperature display
1. Value = 0, Display setpoint temperature (default)  
2. Value = 1, Display calculated temperature
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Display setpoint temperature (default) |
| 1 | Display calculated temperature |

The manufacturer defined default value is ```0``` (Display setpoint temperature (default)).

This parameter has the configuration ID ```config_17_1``` and is of type ```INTEGER```.


### Parameter 18: Button brightness - dimmed state

Button brightness - dimmed state
1. Value = 0 - 100, 0% - 100%, default = 50%
Values in the range 0 to 100 may be set.

The manufacturer defined default value is ```50```.

This parameter has the configuration ID ```config_18_1``` and is of type ```INTEGER```.


### Parameter 19: Button brightness - active state

Button brightness - active state
1. Value = 0 - 100, 0% - 100%, default = 100%
Values in the range 0 to 100 may be set.

The manufacturer defined default value is ```100```.

This parameter has the configuration ID ```config_19_1``` and is of type ```INTEGER```.


### Parameter 20: Display brightness - dimmed state

Display brightness - dimmed state
1. Value = 0 - 100, 0% - 100%, default = 50%
Values in the range 0 to 100 may be set.

The manufacturer defined default value is ```50```.

This parameter has the configuration ID ```config_20_1``` and is of type ```INTEGER```.


### Parameter 21: Display brightness - active state

Display brightness - active state
1. Value = 0 - 100, 0% - 100%, default = 100%
Values in the range 0 to 100 may be set.

The manufacturer defined default value is ```100```.

This parameter has the configuration ID ```config_21_1``` and is of type ```INTEGER```.


### Parameter 22: Temperature report interval

Temperature report interval
1. Value = 0, Reporting of temperature disabled  
2. Value = 1 - 32767, 1s - 32767s, default = 60s

Time interval between consecutive temperature reports.  
Temperature reports can also be sent as a result of polling.
Values in the range 0 to 32767 may be set.

The manufacturer defined default value is ```60```.

This parameter has the configuration ID ```config_22_2``` and is of type ```INTEGER```.


### Parameter 23: Temperature report hysteresis

Temperature report hysteresis
1. Value = 1 - 100, 0.1C - 10.0C, default = 1.0C

The temperature report will be sent if there is a difference in temperature from the previous value reported,  
defined in this parameter (hysteresis).  
Temperature reports can also be sent as a result of polling.
Values in the range 1 to 100 may be set.

The manufacturer defined default value is ```10```.

This parameter has the configuration ID ```config_23_1``` and is of type ```INTEGER```.


### Parameter 24: Meter report interval

Meter report interval
1. Value = 0, Reporting of metering values is disabled  
2. Value = 1 - 32767, 1s - 32767s, default = 60s

Time interval between consecutive meter reports.  
Meter reports can also be sent as a result of polling.
Values in the range 0 to 32767 may be set.

The manufacturer defined default value is ```60```.

This parameter has the configuration ID ```config_24_2``` and is of type ```INTEGER```.


### Parameter 25: Meter report delta value

Meter report delta value
1. Value = 0 - 255, 0kWh - 25.5kWh, default = 1.0kWh

Delta value in kWh between consecutive meter reports.  
Meter reports can also be sent as a result of polling.
Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```10```.

This parameter has the configuration ID ```config_25_1``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The Heatit Z-TRM 2 supports 5 association groups.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.
Lifeline. (Normally used by the Z-Wave Controller)  
Sends:  
- Device Reset Notifications  
- Thermostat Setpoint Reports  
- Thermostat Mode Reports

Association group 1 supports 7 nodes.

### Group 2: Thermostat Binary Switch Set

Send Binary Switch Set commands representing the status of the internal relay.

Association group 2 supports 7 nodes.

### Group 3: Thermostat Internal Multilevel Sensor Reports

Send Multilevel Sensor Reports for internal temperature sensor.

Association group 3 supports 7 nodes.

### Group 4: Thermostat External Multilevel Sensor Reports

Send Multilevel Sensor Reports for external temperature sensor.

Association group 4 supports 7 nodes.

### Group 5: Thermostat Floor Multilevel Sensor Reports

Send Multilevel Sensor Reports for floor temperature sensor.

Association group 5 supports 7 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| |
| COMMAND_CLASS_METER_V3| |
| COMMAND_CLASS_THERMOSTAT_MODE_V1| |
| COMMAND_CLASS_THERMOSTAT_SETPOINT_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_MULTI_CHANNEL_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
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
| COMMAND_CLASS_SWITCH_BINARY_V1| |
| COMMAND_CLASS_METER_V3| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 2

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 3

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 4

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |

### Documentation Links

* [Product Sheet](https://www.opensmarthouse.org/zwavedatabase/854/Heatit-ztrm2.pdf)
* [Manual 2018-06-01](https://www.opensmarthouse.org/zwavedatabase/854/manual-heatit-z-trm2-eng-2018-06-01.pdf)
* [Manual FW 3.4 Ver. 2018-A](https://www.opensmarthouse.org/zwavedatabase/854/A4-Manual-Heatit-Z-TRM2fx-FW-3-4-Ver2018-A-ENG.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/854).
