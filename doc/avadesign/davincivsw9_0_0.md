---
layout: documentation
title: Da Vinci Switch Default - ZWave
---

{% include base.html %}

# Da Vinci Switch Default
This describes the Z-Wave device *Da Vinci Switch Default*, manufactured by *Avadesign Technology Co.* with the thing type UID of ```Avadesign Technology Co._davincivsw9_00_000```.

The device is in the category of *Wall Switch*, defining Any device attached to the wall that controls a binary status of something, for ex. a light switch.

![Da Vinci Switch Default product image](https://opensmarthouse.org/assets/zwave/attachments/911/Contec-Image.jpeg)


The Da Vinci Switch Default supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

The Da Vinci wall controller is a Multi Chanel Z-Wave device that contains up to 6 relays and up to 9 touch buttons that can be set to control either the relays (On/Off switches and shutters) or any other on/off (SWITCH\_BINARY)  , shutter (MULTILEVEL\_SWITCH) Z-Wave device.

### Inclusion Information

Press the #1 button 3 times.

### Exclusion Information

Press the #1 button 3 times.

## Channels

The following table summarises the channels available for the Da Vinci Switch Default -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Dimmer | switch_dimmer | switch_dimmer |  |  | 
| Blinds control | blinds_control | blinds_control |  |  | 
| Scene Number | scene_number | scene_number |  |  | 
| Switch 1 | switch_binary1 | switch_binary |  |  | 
| Scene Number 1 | scene_number1 | scene_number |  |  | 
| Switch 2 | switch_binary2 | switch_binary |  |  | 
| Scene Number 2 | scene_number2 | scene_number |  |  | 
| Switch 3 | switch_binary3 | switch_binary |  |  | 
| Scene Number 3 | scene_number3 | scene_number |  |  | 
| Switch 4 | switch_binary4 | switch_binary |  |  | 
| Scene Number 4 | scene_number4 | scene_number |  |  | 
| Switch 5 | switch_binary5 | switch_binary |  |  | 
| Scene Number 5 | scene_number5 | scene_number |  |  | 
| Switch 6 | switch_binary6 | switch_binary |  |  | 
| Scene Number 6 | scene_number6 | scene_number |  |  | 
| Switch 7 | switch_binary7 | switch_binary |  |  | 
| Scene Number 7 | scene_number7 | scene_number |  |  | 
| Switch 8 | switch_binary8 | switch_binary |  |  | 
| Scene Number 8 | scene_number8 | scene_number |  |  | 
| Switch 9 | switch_binary9 | switch_binary |  |  | 
| Scene Number 9 | scene_number9 | scene_number |  |  | 

### Switch
Channel type information on this channel is not found.

### Dimmer
Channel type information on this channel is not found.

### Blinds control
Channel type information on this channel is not found.

### Scene Number
Channel type information on this channel is not found.

### Switch 1
Channel type information on this channel is not found.

### Scene Number 1
Channel type information on this channel is not found.

### Switch 2
Channel type information on this channel is not found.

### Scene Number 2
Channel type information on this channel is not found.

### Switch 3
Channel type information on this channel is not found.

### Scene Number 3
Channel type information on this channel is not found.

### Switch 4
Channel type information on this channel is not found.

### Scene Number 4
Channel type information on this channel is not found.

### Switch 5
Channel type information on this channel is not found.

### Scene Number 5
Channel type information on this channel is not found.

### Switch 6
Channel type information on this channel is not found.

### Scene Number 6
Channel type information on this channel is not found.

### Switch 7
Channel type information on this channel is not found.

### Scene Number 7
Channel type information on this channel is not found.

### Switch 8
Channel type information on this channel is not found.

### Scene Number 8
Channel type information on this channel is not found.

### Switch 9
Channel type information on this channel is not found.

### Scene Number 9
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 29 configuration parameters available in the Da Vinci Switch Default.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | EP 1 Type | EP 1 Type |
| 2 | EP 1 Partner Id | EP 1 Partner Id |
| 3 | EP 1 Blind Duration | EP 1 Blind Duration |
| 4 | EP 1 Output | EP 1 Output |
| 5 | EP 1 Button attribute | EP 1 Button attribute |
| 6 | EP 2 Type | EP 2 Type |
| 7 | EP 2 Partner Id | EP 2 Partner Id |
| 8 | EP 2 Blind Duration | EP 2 Blind Duration |
| 11 | EP 3 Type | EP 3 Type |
| 12 | EP 3 Partner-Id | EP 3 Partner-Id |
| 13 | EP 3 Blind Duration | EP 3 Blind Duration |
| 16 | EP 4 Type | EP 4 Type |
| 17 | EP 4 Partner-Id | EP 4 Partner-Id |
| 18 | EP 4 Blind Duration | EP 4 Blind Duration |
| 21 | EP 5 Type | EP 5 Type |
| 22 | EP 5 Partner-Id | EP 5 Partner-Id |
| 23 | EP 5 Blind Duration | EP 5 Blind Duration |
| 26 | EP 6 Type | EP 6 Type |
| 27 | EP 6 Partner-Id | EP 6 Partner-Id |
| 28 | EP 6 Blind Duration | EP 6 Blind Duration |
| 31 | EP 7 Type | EP 7 Type |
| 32 | EP 7 Partner-Id | EP 7 Partner-Id |
| 33 | EP 7 Blind Duration | EP 7 Blind Duration |
| 36 | EP 8 Type | EP 8 Type |
| 37 | EP 8 Partner-Id | EP 8 Partner-Id |
| 38 | EP 8 Blind Duration | EP 8 Blind Duration |
| 41 | EP 9 Type | EP 9 Type |
| 42 | EP 9 Partner-Id | EP 9 Partner-Id |
| 43 | EP 9 Blind Duration | EP 9 Blind Duration |

### Parameter 1: EP 1 Type

EP 1 Type
1 = switch on/off

2 = blind up

3 = blind down

4 = switch multiway

5 = blind-up multiway

6 = blind-down multiway
Values in the range 1 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 2: EP 1 Partner Id

EP 1 Partner Id

Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_2_1``` and is of type ```INTEGER```.


### Parameter 3: EP 1 Blind Duration

EP 1 Blind Duration

Values in the range 0 to 127 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_3_1``` and is of type ```INTEGER```.


### Parameter 4: EP 1 Output

EP 1 Output
0 = not used  
1 – 6 = Num. of output
Values in the range 1 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_4_1``` and is of type ```INTEGER```.


### Parameter 5: EP 1 Button attribute

EP 1 Button attribute
Bit [0] = LED enable  
Bit [1] = Sound enable  
Bit [2] = Dry contact enable  
Bit [3] = Motor enable
Values in the range 0 to 7 may be set.

The manufacturer defined default value is ```7```.

This parameter has the configuration ID ```config_5_1``` and is of type ```INTEGER```.


### Parameter 6: EP 2 Type

EP 2 Type
1 = switch on/off

2 = blind up

3 = blind down

4 = switch multiway

5 = blind-up multiway

6 = blind-down multiway
Values in the range 0 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_6_1``` and is of type ```INTEGER```.


### Parameter 7: EP 2 Partner Id

EP 2 Partner Id

Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_7_1``` and is of type ```INTEGER```.


### Parameter 8: EP 2 Blind Duration

EP 2 Blind Duration

Values in the range 0 to 127 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_8_1``` and is of type ```INTEGER```.


### Parameter 11: EP 3 Type

EP 3 Type
1 = switch on/off

2 = blind up

3 = blind down

4 = switch multiway

5 = blind-up multiway

6 = blind-down multiway
Values in the range 0 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_11_1``` and is of type ```INTEGER```.


### Parameter 12: EP 3 Partner-Id

EP 3 Partner-Id

Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_12_1``` and is of type ```INTEGER```.


### Parameter 13: EP 3 Blind Duration

EP 3 Blind Duration

Values in the range 0 to 127 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_13_1``` and is of type ```INTEGER```.


### Parameter 16: EP 4 Type

EP 4 Type
1 = switch on/off

2 = blind up

3 = blind down

4 = switch multiway

5 = blind-up multiway

6 = blind-down multiway
Values in the range 0 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_16_1``` and is of type ```INTEGER```.


### Parameter 17: EP 4 Partner-Id

EP 4 Partner-Id

Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_17_1``` and is of type ```INTEGER```.


### Parameter 18: EP 4 Blind Duration

EP 4 Blind Duration

Values in the range 0 to 127 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_18_1``` and is of type ```INTEGER```.


### Parameter 21: EP 5 Type

EP 5 Type
1 = switch on/off

2 = blind up

3 = blind down

4 = switch multiway

5 = blind-up multiway

6 = blind-down multiway
Values in the range 0 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_21_1``` and is of type ```INTEGER```.


### Parameter 22: EP 5 Partner-Id

EP 5 Partner-Id

Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_22_1``` and is of type ```INTEGER```.


### Parameter 23: EP 5 Blind Duration

EP 5 Blind Duration

Values in the range 0 to 127 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_23_1``` and is of type ```INTEGER```.


### Parameter 26: EP 6 Type

EP 6 Type
1 = switch on/off

2 = blind up

3 = blind down

4 = switch multiway

5 = blind-up multiway

6 = blind-down multiway
Values in the range 0 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_26_1``` and is of type ```INTEGER```.


### Parameter 27: EP 6 Partner-Id

EP 6 Partner-Id

Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_27_1``` and is of type ```INTEGER```.


### Parameter 28: EP 6 Blind Duration

EP 6 Blind Duration

Values in the range 0 to 127 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_28_1``` and is of type ```INTEGER```.


### Parameter 31: EP 7 Type

EP 7 Type
1 = switch on/off

2 = blind up

3 = blind down

4 = switch multiway

5 = blind-up multiway

6 = blind-down multiway
Values in the range 0 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_31_1``` and is of type ```INTEGER```.


### Parameter 32: EP 7 Partner-Id

EP 7 Partner-Id

Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_32_1``` and is of type ```INTEGER```.


### Parameter 33: EP 7 Blind Duration

EP 7 Blind Duration

Values in the range 0 to 127 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_33_1``` and is of type ```INTEGER```.


### Parameter 36: EP 8 Type

EP 8 Type
1 = switch on/off

2 = blind up

3 = blind down

4 = switch multiway

5 = blind-up multiway

6 = blind-down multiway
Values in the range 0 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_36_1``` and is of type ```INTEGER```.


### Parameter 37: EP 8 Partner-Id

EP 8 Partner-Id

Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_37_1``` and is of type ```INTEGER```.


### Parameter 38: EP 8 Blind Duration

EP 8 Blind Duration

Values in the range 0 to 127 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_38_1``` and is of type ```INTEGER```.


### Parameter 41: EP 9 Type

EP 9 Type
1 = switch on/off

2 = blind up

3 = blind down

4 = switch multiway

5 = blind-up multiway

6 = blind-down multiway
Values in the range 0 to 6 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_41_1``` and is of type ```INTEGER```.


### Parameter 42: EP 9 Partner-Id

EP 9 Partner-Id

Values in the range 0 to 9 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_42_1``` and is of type ```INTEGER```.


### Parameter 43: EP 9 Blind Duration

EP 9 Blind Duration

Values in the range 0 to 127 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_43_1``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The Da Vinci Switch Default supports 1 association group.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.

Association group 1 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_MULTI_CHANNEL_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 1

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 2

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 3

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 4

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 5

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 6

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 7

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 8

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |
#### Endpoint 9

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_CENTRAL_SCENE_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_MULTI_CHANNEL_ASSOCIATION_V3| |

### Documentation Links

* [Manual](https://www.opensmarthouse.org/zwavedatabase/911/DA-VINCI-ver-9.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/911).
