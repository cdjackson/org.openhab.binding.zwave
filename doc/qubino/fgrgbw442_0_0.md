---
layout: documentation
title: FGRGBW-442 - ZWave
---

{% include base.html %}

# FGRGBW-442 RGBW CONTROLLER 2
This describes the Z-Wave device *FGRGBW-442*, manufactured by *[Fibargroup](http://www.fibaro.com/)* with the thing type UID of ```Fibargroup_fgrgbw442_00_000```.

The device is in the category of *Light Bulb*, defining Devices that illuminate something, such as bulbs, etc..

![FGRGBW-442 product image](https://opensmarthouse.org/assets/zwave/attachments/1127/rgbwcontroller2.png)


The FGRGBW-442 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

FIBARO RGBW Controller 2 uses PWM output signal, allowing it to control LED, RGB, RGBW strips, halogen lights and other resistive loads. It can also measure active power and energy consumed by the load. Controlled devices may be powered by 12 or 24V DC.

Inputs support momentary/toggle switches and 0-10V analog sensors, like temperature sensors, humidity sensors, light sensors etc

### Inclusion Information

Quickly, three times click the service button.

### Exclusion Information

Quickly, three times click the service button.

## Channels

The following table summarises the channels available for the FGRGBW-442 -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Dimmer | switch_dimmer | switch_dimmer |  |  | 
| Sensor (voltage) | sensor_voltage | sensor_voltage |  |  | 
| Electric meter (watts) | meter_watts | meter_watts |  |  | 
| Electric meter (kWh) | meter_kwh | meter_kwh |  |  | 
| Color Control | color_color | color_color |  |  | 
| Color Temperature | color_temperature | color_temperature |  |  | 
| Scene Number | scene_number | scene_number |  |  | 
| Start programmed sequence | config_decimal | config_decimal |  |  | 
| Alarm (power) | alarm_power | alarm_power |  |  | 
| Alarm (system) | alarm_system | alarm_system |  |  | 
| Dimmer 1 | switch_dimmer1 | switch_dimmer |  |  | 
| Electric meter (watts) 1 | meter_watts1 | meter_watts |  |  | 
| Electric meter (kWh) 1 | meter_kwh1 | meter_kwh |  |  | 
| Color Control 1 | color_color1 | color_color |  |  | 
| Color Temperature 1 | color_temperature1 | color_temperature |  |  | 
| Alarm (power) 1 | alarm_power1 | alarm_power |  |  | 
| Alarm (system) 1 | alarm_system1 | alarm_system |  |  | 
| Dimmer 2 | switch_dimmer2 | switch_dimmer |  |  | 
| Dimmer 3 | switch_dimmer3 | switch_dimmer |  |  | 
| Dimmer 4 | switch_dimmer4 | switch_dimmer |  |  | 
| Dimmer 5 | switch_dimmer5 | switch_dimmer |  |  | 
| Sensor (voltage) 6 | sensor_voltage6 | sensor_voltage |  |  | 
| Sensor (voltage) 7 | sensor_voltage7 | sensor_voltage |  |  | 
| Sensor (voltage) 8 | sensor_voltage8 | sensor_voltage |  |  | 
| Sensor (voltage) 9 | sensor_voltage9 | sensor_voltage |  |  | 

### Dimmer
Channel type information on this channel is not found.

### Sensor (voltage)
Channel type information on this channel is not found.

### Electric meter (watts)
Channel type information on this channel is not found.

### Electric meter (kWh)
Channel type information on this channel is not found.

### Color Control
Channel type information on this channel is not found.

### Color Temperature
Channel type information on this channel is not found.

### Scene Number
Channel type information on this channel is not found.

### Start programmed sequence
Channel type information on this channel is not found.

### Alarm (power)
Channel type information on this channel is not found.

### Alarm (system)
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

### Alarm (power) 1
Channel type information on this channel is not found.

### Alarm (system) 1
Channel type information on this channel is not found.

### Dimmer 2
Channel type information on this channel is not found.

### Dimmer 3
Channel type information on this channel is not found.

### Dimmer 4
Channel type information on this channel is not found.

### Dimmer 5
Channel type information on this channel is not found.

### Sensor (voltage) 6
Channel type information on this channel is not found.

### Sensor (voltage) 7
Channel type information on this channel is not found.

### Sensor (voltage) 8
Channel type information on this channel is not found.

### Sensor (voltage) 9
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 39 configuration parameters available in the FGRGBW-442.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Remember device status before the power failure |  |
| 20 | Input 1 - operating mode | Input 1 - operating mode |
| 21 | Input 2 - operating mode | Input 2 - operating mode |
| 22 | Input 3 - operating mode | Input 3 - operating mode |
| 23 | Input 4 - operating mode | Input 4 - operating mode |
| 30 | Alarm configuration - 1st slot | Alarm configuration - 1st slot |
| 31 | Alarm configuration - 2nd slot | Alarm configuration - 2nd slot |
| 32 | Alarm configuration - 3rd slot | Alarm configuration - 3rd slot |
| 33 | Alarm configuration - 4th slot | Alarm configuration - 4th slot |
| 34 | Alarm configuration - 5th slot | Alarm configuration - 5th slot |
| 35 | Duration of alarm signalization | Duration of alarm signalization |
| 40 | Input 1 - sent scenes | Input 1 - sent scenes |
| 41 | Input 2 - sent scenes | Input 2 - sent scenes |
| 42 | Input 3 - sent scenes | Input 3 - sent scenes |
| 43 | Input 4 - sent scenes | Input 4 - sent scenes |
| 62 | Power reports - periodic | Power reports - periodic |
| 63 | Analog inputs output change on input change | Analog inputs output change on input change |
| 64 | Analog inputs reports - periodic | Analog inputs reports - periodic |
| 65 | Energy reports - on change | Energy reports - on change |
| 66 | Energy reports - periodic | Energy reports - periodic |
| 150 | Inputs - LED colour control mode | Inputs - LED colour control mode |
| 151 | Local control - transition time | Local control - transition time |
| 152 | Remote control - transition time | Remote control - transition time |
| 154 | ON frame value for single click | ON frame value for single click |
| 154 | ON frame value for single click IN1 | ON frame value for single click IN1 |
| 154 | ON frame value for single click IN2 | ON frame value for single click IN2 |
| 154 | ON frame value for single click IN3 | ON frame value for single click IN3 |
| 154 | ON frame value for single click IN4 | ON frame value for single click IN4 |
| 155 | OFF frame value for single click | OFF frame value for single click |
| 155 | OFF frame value for single click IN1 | OFF frame value for single click IN1 |
| 155 | OFF frame value for single click IN2 | OFF frame value for single click IN2 |
| 155 | OFF frame value for single click IN3 | OFF frame value for single click IN3 |
| 155 | OFF frame value for single click IN4 | OFF frame value for single click IN4 |
| 156 | ON frame value for double click | ON frame value for double click |
| 156 | ON frame value for double click IN1 | ON frame value for double click IN1 |
| 156 | ON frame value for double click IN2 | ON frame value for double click IN2 |
| 156 | ON frame value for double click IN3 | ON frame value for double click IN3 |
| 156 | ON frame value for double click IN4 | ON frame value for double click IN4 |
| 157 | Start programmed sequence | Start programmed sequence |

### Parameter 1: Remember device status before the power failure



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | device remains switched off |
| 1 | restore the state |

The manufacturer defined default value is ```0``` (device remains switched off).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 20: Input 1 - operating mode

Input 1 - operating mode

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Analog input without internal pull-up |
| 1 | Analog input with internal pull-up |
| 2 | Momentary switch (Central Scene) |
| 3 | Toggle switch: switch state on every input change |
| 4 | Toggle switch: closed – ON, opened – OFF |

The manufacturer defined default value is ```2``` (Momentary switch (Central Scene)).

This parameter has the configuration ID ```config_20_1``` and is of type ```INTEGER```.


### Parameter 21: Input 2 - operating mode

Input 2 - operating mode

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Analog input without internal pull-up |
| 1 | Analog input with internal pull-up |
| 2 | Momentary switch (Central Scene) |
| 3 | Toggle switch: switch state on every input change |
| 4 | Toggle switch: closed – ON, opened – OFF |

The manufacturer defined default value is ```2``` (Momentary switch (Central Scene)).

This parameter has the configuration ID ```config_21_1``` and is of type ```INTEGER```.


### Parameter 22: Input 3 - operating mode

Input 3 - operating mode

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Analog input without internal pull-up |
| 1 | Analog input with internal pull-up |
| 2 | Momentary switch (Central Scene) |
| 3 | Toggle switch: switch state on every input change |
| 4 | Toggle switch: closed – ON, opened – OFF |

The manufacturer defined default value is ```2``` (Momentary switch (Central Scene)).

This parameter has the configuration ID ```config_22_1``` and is of type ```INTEGER```.


### Parameter 23: Input 4 - operating mode

Input 4 - operating mode

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Analog input without internal pull-up |
| 1 | Analog input with internal pull-up |
| 2 | Momentary switch (Central Scene) |
| 3 | Toggle switch: switch state on every input change |
| 4 | Toggle switch:closed – ON, opened – OF |

The manufacturer defined default value is ```2``` (Momentary switch (Central Scene)).

This parameter has the configuration ID ```config_23_1``` and is of type ```INTEGER```.


### Parameter 30: Alarm configuration - 1st slot

Alarm configuration - 1st slot

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_30_4_000000FF``` and is of type ```INTEGER```.


### Parameter 31: Alarm configuration - 2nd slot

Alarm configuration - 2nd slot

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_31_4_000000FF``` and is of type ```INTEGER```.


### Parameter 32: Alarm configuration - 3rd slot

Alarm configuration - 3rd slot

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_32_4_000000FF``` and is of type ```INTEGER```.


### Parameter 33: Alarm configuration - 4th slot

Alarm configuration - 4th slot

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_33_4_000000FF``` and is of type ```INTEGER```.


### Parameter 34: Alarm configuration - 5th slot

Alarm configuration - 5th slot

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_34_4_000000FF``` and is of type ```INTEGER```.


### Parameter 35: Duration of alarm signalization

Duration of alarm signalization

The following option values may be configured, in addition to values in the range 0 to 32400 -:

| Value  | Description |
|--------|-------------|
| 0 | infinite signalization |

The manufacturer defined default value is ```600```.

This parameter has the configuration ID ```config_35_2_0000FFFF``` and is of type ```INTEGER```.


### Parameter 40: Input 1 - sent scenes

Input 1 - sent scenes

Values in the range 0 to 15 may be set.

The manufacturer defined default value is ```15```.

This parameter has the configuration ID ```config_40_1``` and is of type ```INTEGER```.


### Parameter 41: Input 2 - sent scenes

Input 2 - sent scenes

Values in the range 0 to 15 may be set.

The manufacturer defined default value is ```15```.

This parameter has the configuration ID ```config_41_1``` and is of type ```INTEGER```.


### Parameter 42: Input 3 - sent scenes

Input 3 - sent scenes

Values in the range 0 to 15 may be set.

The manufacturer defined default value is ```15```.

This parameter has the configuration ID ```config_42_1``` and is of type ```INTEGER```.


### Parameter 43: Input 4 - sent scenes

Input 4 - sent scenes

Values in the range 0 to 15 may be set.

The manufacturer defined default value is ```15```.

This parameter has the configuration ID ```config_43_1``` and is of type ```INTEGER```.


### Parameter 62: Power reports - periodic

Power reports - periodic
This parameter determines in what time intervals the periodic power reports are sent to the main controller. Periodic reports do not depend of power change (parameter 61).

  * 0 - periodic reports are disabled
  * 30-32400 (30-32400s) - report interval
  * Default - 3600 (1h)
Values in the range 0 to 32400 may be set.

The manufacturer defined default value is ```3600```.

This parameter has the configuration ID ```config_62_2``` and is of type ```INTEGER```.


### Parameter 63: Analog inputs output change on input change

Analog inputs output change on input change
# Analog inputs reports and output change on input change

This parameter defines minimal change (from the last reported) of analog input voltage that results in sending new report and change in the output value. Parameter is relevant only for analog inpu ts (parameter 20, 21, 22 or 23 set to 0 or 1).

  * 0 - reporting on change disabled
  * 1-100 (0.1-10V, 0.1V step)
  * Default - 5 (0.5V)
Values in the range 0 to 100 may be set.

The manufacturer defined default value is ```5```.

This parameter has the configuration ID ```config_63_2``` and is of type ```INTEGER```.


### Parameter 64: Analog inputs reports - periodic

Analog inputs reports - periodic
This parameter defines reporting period of analog inputs value.

Periodical reports are independent from changes in value (parameter 63).

Parameter is relevant only for analog inputs (parameter 20, 21, 22 or 23 set to 0 or 1)

  * 0 – periodical reports disabled
  * 30-32400 (30-32400s, 1s step)
Values in the range 0 to 32400 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_64_2``` and is of type ```INTEGER```.


### Parameter 65: Energy reports - on change

Energy reports - on change
This parameter determines the minimum change in consumed energy that will result in sending new energy report to the main controller. Energy reports are sent no often than every 30 seconds.

  * 0 - reports are disabled
  * 1-500 (0.01 - 5 kWh) - change in energy
Values in the range 0 to 500 may be set.

The manufacturer defined default value is ```10```.

This parameter has the configuration ID ```config_65_2``` and is of type ```INTEGER```.


### Parameter 66: Energy reports - periodic

Energy reports - periodic
This parameter determines in what time intervals the periodic energy reports are sent to the main controller. Periodic reports do not depend of energy change (parameter 65)

  * 0 - periodic reports are disabled
  * 30-32400 (30-32400s) - report interval
Values in the range 0 to 32400 may be set.

The manufacturer defined default value is ```3600```.

This parameter has the configuration ID ```config_66_2``` and is of type ```INTEGER```.


### Parameter 150: Inputs - LED colour control mode

Inputs - LED colour control mode

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | RGBW mode |
| 1 | HSB and White mode |

The manufacturer defined default value is ```0``` (RGBW mode).

This parameter has the configuration ID ```config_150_1``` and is of type ```INTEGER```.


### Parameter 151: Local control - transition time

Local control - transition time
This parameter determines time of smooth transition between 0% and 100% when controlling with connected switches.

  * 0 – instantly
  * 1-127 (1s-127s, 1s step)
  * 128-254 (1min-127min, 1min step)
Values in the range 0 to 254 may be set.

The manufacturer defined default value is ```3```.

This parameter has the configuration ID ```config_151_2``` and is of type ```INTEGER```.


### Parameter 152: Remote control - transition time

Remote control - transition time
This parameter determines time needed to change the state between current and target values when controlling via Z-Wave network.

  * 0 – instantly
  * 1-127 (1s-127s, 1s step)
  * 128-254 (1min-127min, 1min step)
Values in the range 0 to 254 may be set.

The manufacturer defined default value is ```3```.

This parameter has the configuration ID ```config_152_2``` and is of type ```INTEGER```.


### Parameter 154: ON frame value for single click

ON frame value for single click
This is an advanced parameter and will therefore not show in the user interface without entering advanced mode.
Values in the range 0 to 4294967295 may be set.

The manufacturer defined default value is ```4294967295```.

This parameter has the configuration ID ```config_154_4``` and is of type ```INTEGER```.


### Parameter 154: ON frame value for single click IN1

ON frame value for single click IN1

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_154_4_000000FF``` and is of type ```INTEGER```.


### Parameter 154: ON frame value for single click IN2

ON frame value for single click IN2

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_154_4_0000FF00``` and is of type ```INTEGER```.


### Parameter 154: ON frame value for single click IN3

ON frame value for single click IN3

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_154_4_00FF0000``` and is of type ```INTEGER```.


### Parameter 154: ON frame value for single click IN4

ON frame value for single click IN4

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_154_4_7F000000``` and is of type ```INTEGER```.


### Parameter 155: OFF frame value for single click

OFF frame value for single click
This is an advanced parameter and will therefore not show in the user interface without entering advanced mode.
Values in the range 0 to 4294967295 may be set.

The manufacturer defined default value is ```4294967295```.

This parameter has the configuration ID ```config_155_4``` and is of type ```INTEGER```.


### Parameter 155: OFF frame value for single click IN1

OFF frame value for single click IN1

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_155_4_000000FF``` and is of type ```INTEGER```.


### Parameter 155: OFF frame value for single click IN2

OFF frame value for single click IN2

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_155_4_0000FF00``` and is of type ```INTEGER```.


### Parameter 155: OFF frame value for single click IN3

OFF frame value for single click IN3

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_155_4_00FF0000``` and is of type ```INTEGER```.


### Parameter 155: OFF frame value for single click IN4

OFF frame value for single click IN4

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_155_4_7F000000``` and is of type ```INTEGER```.


### Parameter 156: ON frame value for double click

ON frame value for double click
This is an advanced parameter and will therefore not show in the user interface without entering advanced mode.
Values in the range 0 to 4294967295 may be set.

The manufacturer defined default value is ```4294967295```.

This parameter has the configuration ID ```config_156_4``` and is of type ```INTEGER```.


### Parameter 156: ON frame value for double click IN1

ON frame value for double click IN1

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_156_4_000000FF``` and is of type ```INTEGER```.


### Parameter 156: ON frame value for double click IN2

ON frame value for double click IN2

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_156_4_0000FF00``` and is of type ```INTEGER```.


### Parameter 156: ON frame value for double click IN3

ON frame value for double click IN3

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_156_4_00FF0000``` and is of type ```INTEGER```.


### Parameter 156: ON frame value for double click IN4

ON frame value for double click IN4

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```255```.

This parameter has the configuration ID ```config_156_4_7F000000``` and is of type ```INTEGER```.


### Parameter 157: Start programmed sequence

Start programmed sequence
Setting this parameter will start programmed sequence with selected number. User can define own sequences via controller. While the sequence is active, the menu is unavailable.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | sequence inactive |
| 1 | user-defined sequence 1 |
| 2 | user-defined sequence 2 |
| 3 | user-defined sequence 3 |
| 4 | user-defined sequence 4 |
| 5 | user-defined sequence 5 |
| 6 | Fireplace sequence |
| 7 | Storm sequence |
| 8 | Rainbow sequence |
| 9 | Aurora sequence |
| 10 | Police (red-white-blue) sequence |

The manufacturer defined default value is ```0``` (sequence inactive).

This parameter has the configuration ID ```config_157_1``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The FGRGBW-442 supports 10 association groups.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.

Association group 1 supports 1 node.

### Group 2: RGBW Sync

allows to synchronize state of other FIBARO RGBW Controller devices (FGRGBW-442 and FGRGBWM- 441)

- do not use with other devices.

Association group 2 supports 5 nodes.

### Group 3: On/Off (IN1)

used to turn the associated devices on/off reflecting IN1 operation.

Association group 3 supports 5 nodes.

### Group 4: Dimmer (IN1)

used to change level of associated devices reflecting IN1 operation.

Association group 4 supports 5 nodes.

### Group 5: On/Off (IN2)

used to turn the associated devices on/off reflecting IN2 operation.

Association group 5 supports 5 nodes.

### Group 6: Dimmer (IN2)

used to change level of associated devices reflecting IN2 operation.

Association group 6 supports 5 nodes.

### Group 7: On/Off (IN3)

used to turn the associated devices on/off reflecting IN3 operation.

Association group 7 supports 5 nodes.

### Group 8: Dimmer (IN3)

used to change level of associated devices reflecting IN3 operation.

Association group 8 supports 5 nodes.

### Group 9: On/Off (IN4)

used to turn the associated devices on/off reflecting IN4 operation.

Association group 9 supports 5 nodes.

### Group 10: Dimmer (IN4)

used to change level of associated devices reflecting IN4 operation.

Association group 10 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V10| |
| COMMAND_CLASS_METER_V3| |
| COMMAND_CLASS_SWITCH_COLOR_V3| Linked to BASIC|
| COMMAND_CLASS_CRC_16_ENCAP_V1| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V3| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_MULTI_CHANNEL_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V8| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_PROTECTION_V2| |
| COMMAND_CLASS_FIRMWARE_UPDATE_MD_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 1

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| Linked to BASIC|
| COMMAND_CLASS_METER_V3| |
| COMMAND_CLASS_SWITCH_COLOR_V3| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ALARM_V8| |
| COMMAND_CLASS_PROTECTION_V2| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 2

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 3

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 4

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 5

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 6

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V10| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 7

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V10| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 8

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V10| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |
#### Endpoint 9

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_APPLICATION_STATUS_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V10| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
| COMMAND_CLASS_SECURITY_V1| |

### Documentation Links

* [Manual](https://www.opensmarthouse.org/zwavedatabase/1127/FGRGBW-442-EN-T-v1-0.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/1127).
