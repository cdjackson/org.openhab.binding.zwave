---
layout: documentation
title: Vitrum Satellite VI - ZWave
---

{% include base.html %}

# Vitrum Satellite VI Vitrum touch switch satellite 6 buttons
This describes the Z-Wave device *Vitrum Satellite VI*, manufactured by *VDA* with the thing type UID of ```VDA_satellitevi_00_000```.

The Vitrum Satellite VI supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

When the device is in the stand-alone mode and is not included in a Z-Wave network the illuminated ring around the touch keys will light red for a moment when passing from one mode to another.

Each button can be configured in 4 different modes. Press the 2 service buttons (left and right each) for at least 8 seconds. Buttons will start to flash and the color of the flashing ring will indicate the channel setting:

- Yellow: for association with On-Off Modules, toggle-button function (BASIC)

- Red: for association with On-Off Modules, push-button function (BASIC)

- Magenta: for association with Roller Blinds, 2 buttons will start flashing together for up and down movement (SWITCH_MULTILEVEL)

- Green: for association with Dimmer Modules (SWITCH_MULTILEVEL)

After mode selection, please proceed with inclusion process.

### Inclusion Information

With the controller in the inclusion mode, press any of the touch keys on the device. Vitrum indicates that it has been included to the network by flashing the yellow LEDs three times and switching on all the lights connected to the unit.

### Exclusion Information

Press and hold the leftmost touch key for at least 8 seconds. The device will flash red three times and sound an acoustic signal to indicate that the original factory setting has been restored.

## Channels

The following table summarises the channels available for the Vitrum Satellite VI -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Dimmer | switch_dimmer | switch_dimmer |  |  | 
| Dimmer 1 | switch_dimmer1 | switch_dimmer |  |  | 
| Dimmer 2 | switch_dimmer2 | switch_dimmer |  |  | 
| Dimmer 3 | switch_dimmer3 | switch_dimmer |  |  | 
| Dimmer 4 | switch_dimmer4 | switch_dimmer |  |  | 
| Dimmer 5 | switch_dimmer5 | switch_dimmer |  |  | 
| Dimmer 6 | switch_dimmer6 | switch_dimmer |  |  | 

### Switch
Channel type information on this channel is not found.

### Dimmer
Channel type information on this channel is not found.

### Dimmer 1
Channel type information on this channel is not found.

### Dimmer 2
Channel type information on this channel is not found.

### Dimmer 3
Channel type information on this channel is not found.

### Dimmer 4
Channel type information on this channel is not found.

### Dimmer 5
Channel type information on this channel is not found.

### Dimmer 6
Channel type information on this channel is not found.



## Device Configuration

The device has no configuration parameters defined.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The Vitrum Satellite VI supports 6 association groups.

### Group 1: Button channel 1

Control up to 5 devices with this button. The kind of device controlled depends on the Button configuration.

Association group 1 supports 5 nodes.

### Group 2: Button channel 2

Control up to 5 devices with this button. The kind of device controlled depends on the Button configuration.

Association group 2 supports 5 nodes.

### Group 3: Button channel 3

Control up to 5 devices with this button. The kind of device controlled depends on the Button configuration.

Association group 3 supports 5 nodes.

### Group 4: Button channel 4

Control up to 5 devices with this button. The kind of device controlled depends on the Button configuration.

Association group 4 supports 5 nodes.

### Group 5: Button channel 5

Control up to 5 devices with this button. The kind of device controlled depends on the Button configuration.

Association group 5 supports 5 nodes.

### Group 6: Button channel 6

Control up to 5 devices with this button. The kind of device controlled depends on the Button configuration.

Association group 6 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V1| Linked to BASIC|
| COMMAND_CLASS_SWITCH_ALL_V1| |
| COMMAND_CLASS_MULTI_CHANNEL_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_NODE_NAMING_V1| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V1| |
| COMMAND_CLASS_INDICATOR_V1| |
#### Endpoint 1

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V1| Linked to BASIC|
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_VERSION_V1| |
#### Endpoint 2

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V1| Linked to BASIC|
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_VERSION_V1| |
#### Endpoint 3

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V1| Linked to BASIC|
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_VERSION_V1| |
#### Endpoint 4

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V1| Linked to BASIC|
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_VERSION_V1| |
#### Endpoint 5

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V1| Linked to BASIC|
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_VERSION_V1| |
#### Endpoint 6

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V1| Linked to BASIC|
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_VERSION_V1| |

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/626).
