---
layout: documentation
title: GWPN5 - ZWave
---

{% include base.html %}

# GWPN5 Multi-socket PowerNode (5-plug)
This describes the Z-Wave device *GWPN5*, manufactured by *GreenWave Reality Inc.* with the thing type UID of ```GreenWave Reality Inc._gwpn5_00_000```.

The device is in the category of *Power Outlet*, defining Small devices to be plugged into a power socket in a wall which stick there.

![GWPN5 product image](https://opensmarthouse.org/assets/zwave/attachments/264/gwpn5.png)


The GWPN5 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

This Configuration is for the 6 plug version of the PowerNode.

### Inclusion Information

On the PowerNode, press and hold the **sync** button for approximately one second until the activity indicator displays a clockwise rotating pattern. This indicates the PowerNode is attempting inclusion. During this process, verify that the Gateway activity indicator still displays a clockwise rotating pattern.

After a few seconds, the rotating pattern on both the PowerNode and the Gateway stops. All bars turn green forming a circle for several seconds. This indicates a successful inclusion.

If all bars on the activity indicator start flashing instead of forming a solid circle, then the PowerNode inclusion process has failed, and you must start the sync process again. If syncing continually fails even though the PowerNode is close to the Gateway, then it may be an indication of a hardware fault, and the PowerNode might need replacing.

### Exclusion Information

On the PowerNode, press and hold the **Sync** button for approximately one second until the PowerNode activity indicator begins to display a counter-clockwise rotating pattern. The PowerNode is attempting exclusion.

## Channels

The following table summarises the channels available for the GWPN5 -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Electric meter (watts) | meter_watts | meter_watts |  |  | 
| Electric meter (kWh) | meter_kwh | meter_kwh |  |  | 
| Alarm | alarm_general | alarm_general |  |  | 
| Switch 1 | switch_binary1 | switch_binary |  |  | 
| Electric meter (watts) 1 | meter_watts1 | meter_watts |  |  | 
| Electric meter (kWh) 1 | meter_kwh1 | meter_kwh |  |  | 
| Switch 2 | switch_binary2 | switch_binary |  |  | 
| Electric meter (watts) 2 | meter_watts2 | meter_watts |  |  | 
| Electric meter (kWh) 2 | meter_kwh2 | meter_kwh |  |  | 
| Switch 3 | switch_binary3 | switch_binary |  |  | 
| Electric meter (watts) 3 | meter_watts3 | meter_watts |  |  | 
| Electric meter (kWh) 3 | meter_kwh3 | meter_kwh |  |  | 
| Switch 4 | switch_binary4 | switch_binary |  |  | 
| Electric meter (watts) 4 | meter_watts4 | meter_watts |  |  | 
| Electric meter (kWh) 4 | meter_kwh4 | meter_kwh |  |  | 
| Switch 5 | switch_binary5 | switch_binary |  |  | 
| Electric meter (watts) 5 | meter_watts5 | meter_watts |  |  | 
| Electric meter (kWh) 5 | meter_kwh5 | meter_kwh |  |  | 

### Switch
Channel type information on this channel is not found.

### Electric meter (watts)
Channel type information on this channel is not found.

### Electric meter (kWh)
Channel type information on this channel is not found.

### Alarm
Channel type information on this channel is not found.

### Switch 1
Channel type information on this channel is not found.

### Electric meter (watts) 1
Channel type information on this channel is not found.

### Electric meter (kWh) 1
Channel type information on this channel is not found.

### Switch 2
Channel type information on this channel is not found.

### Electric meter (watts) 2
Channel type information on this channel is not found.

### Electric meter (kWh) 2
Channel type information on this channel is not found.

### Switch 3
Channel type information on this channel is not found.

### Electric meter (watts) 3
Channel type information on this channel is not found.

### Electric meter (kWh) 3
Channel type information on this channel is not found.

### Switch 4
Channel type information on this channel is not found.

### Electric meter (watts) 4
Channel type information on this channel is not found.

### Electric meter (kWh) 4
Channel type information on this channel is not found.

### Switch 5
Channel type information on this channel is not found.

### Electric meter (watts) 5
Channel type information on this channel is not found.

### Electric meter (kWh) 5
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 5 configuration parameters available in the GWPN5.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 0 | Min. variation of load current | Minimum variation in load current before a message is sent. |
| 1 | No communication light | Minutes after which the device will flash if controller communicate is lost |
| 2 | Wheel position | Wheel position on the GreenWave device (read-only) |
| 3 | Power-on state | Default state after power loss |
| 4 | LED for network  error | If the LED should indicate a network error by flashing or not |
|  | Switch All Mode | Set the mode for the switch when receiving SWITCH ALL commands |

### Parameter 0: Min. variation of load current

Minimum variation in load current before a message is sent.
Value in percent (30 => 30%)
Values in the range 0 to 100 may be set.

The manufacturer defined default value is ```10```.

This parameter has the configuration ID ```config_0_1``` and is of type ```INTEGER```.


### Parameter 1: No communication light

Minutes after which the device will flash if controller communicate is lost

Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```2```.

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 2: Wheel position

Wheel position on the GreenWave device (read-only)

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 128 | Black |
| 129 | Green |
| 130 | Dark Blue |
| 131 | Red |
| 132 | Yellow |
| 133 | Purple |
| 134 | Orange |
| 135 | Light Blue |
| 136 | Pink |
| 137 | Locked |

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_2_1``` and is of type ```INTEGER```.


### Parameter 3: Power-on state

Default state after power loss

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | All OFF |
| 1 | Remember last state |
| 2 | All ON |

The manufacturer defined default value is ```2``` (All ON).

This parameter has the configuration ID ```config_3_1``` and is of type ```INTEGER```.


### Parameter 4: LED for network  error

If the LED should indicate a network error by flashing or not

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Disable the LED for network error |
| 1 | Enable the LED for network error |

The manufacturer defined default value is ```1``` (Enable the LED for network error).

This parameter has the configuration ID ```config_4_1``` and is of type ```INTEGER```.

### Switch All Mode

Set the mode for the switch when receiving SWITCH ALL commands.

The following option values may be configured -:
| Value  | Description |
|--------|-------------|
| 0 | Exclude from All On and All Off groups |
| 1 | Include in All On group |
| 2 | Include in All Off group |
| 255 | Include in All On and All Off groups |

This parameter has the configuration ID ```switchall_mode``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The GWPN5 supports 4 association groups.

### Group 1: Wheel position change


Association group 1 supports 1 node.

### Group 2: Current leakage on relay


Association group 2 supports 1 node.

### Group 3: Power level change

The new power reading is sent if the delta of the change is greater than the defined minimum variation

Association group 3 supports 1 node.

### Group 4: Over-current detection


Association group 4 supports 1 node.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_SWITCH_ALL_V1| |
| COMMAND_CLASS_METER_V2| |
| COMMAND_CLASS_CRC_16_ENCAP_V1| |
| COMMAND_CLASS_MULTI_CHANNEL_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_ASSOCIATION_V1| |
| COMMAND_CLASS_VERSION_V1| |
#### Endpoint 1

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_METER_V2| |
#### Endpoint 2

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_METER_V2| |
#### Endpoint 3

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_METER_V2| |
#### Endpoint 4

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_METER_V2| |
#### Endpoint 5

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_METER_V2| |

### Documentation Links

* [Owner Manual](https://www.opensmarthouse.org/zwavedatabase/264/z-wave-greenwave-powernode-manual.pdf)
* [Technical Manual](https://www.opensmarthouse.org/zwavedatabase/264/Technical-Doc-for-the-powernodes.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/264).
