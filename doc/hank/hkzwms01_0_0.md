---
layout: documentation
title: HKZW_MS01 - ZWave
---

{% include base.html %}

# HKZW_MS01 Multisensor
This describes the Z-Wave device *HKZW_MS01*, manufactured by *[Hank](http://www.hank-tech.com/)* with the thing type UID of ```Hank_hkzwms01_00_000```.

The device is in the category of *Sensor*, defining Device used to measure something.

![HKZW_MS01 product image](https://opensmarthouse.org/assets/zwave/attachments/675/HKZW-MS01.png)


The HKZW_MS01 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

The HKZW_MS01 does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. Refer to the *Wakeup Information* section below for further information.

## Overview

Detects motion, temperature, humidity, and luminance

### Inclusion Information

Triple click the Z-Button

Hold Z-button for 3 seconds for secure inclusion

### Exclusion Information

Triple click the Z-Button

### Wakeup Information

The HKZW_MS01 does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. The wakeup period can be configured in the user interface - it is advisable not to make this too short as it will impact battery life - a reasonable compromise is 1 hour.

The wakeup period does not impact the devices ability to report events or sensor data. The device can be manually woken with a button press on the device as described below - note that triggering a device to send an event is not the same as a wakeup notification, and this will not allow the controller to communicate with the device.


Press the Z-Button

## Channels

The following table summarises the channels available for the HKZW_MS01 -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Sensor (temperature) | sensor_temperature | sensor_temperature |  |  | 
| Sensor (relative humidity) | sensor_relhumidity | sensor_relhumidity |  |  | 
| Sensor (luminance) | sensor_luminance | sensor_luminance |  |  | 
| Alarm (burglar) | alarm_burglar | alarm_burglar |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |

### Sensor (temperature)
Channel type information on this channel is not found.

### Sensor (relative humidity)
Channel type information on this channel is not found.

### Sensor (luminance)
Channel type information on this channel is not found.

### Alarm (burglar)
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 3 configuration parameters available in the HKZW_MS01.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 12 | Motion Sensor`s Sensitivity | The higher the value,the more sensitive the PIR sensor |
| 14 | Enable/Disable Basic Set Command | The motion Sensor can reverse its value of BASIC SET when motion is triggered |
| 15 | value of basic set command |  |
|  | Wakeup Interval | Sets the interval at which the device will accept commands from the controller |
|  | Wakeup Node | Sets the node ID of the device to receive the wakeup notifications |

### Parameter 12: Motion Sensor`s Sensitivity

The higher the value,the more sensitive the PIR sensor

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 1 | Sensitivity 1 |
| 2 | Sensitivity 2 |
| 3 | Sensitivity 3 |
| 4 | Sensitivity 4 |
| 5 | Sensitivity 5 |
| 6 | Sensitivity 6 |
| 7 | Sensitivity 7 |
| 8 | Sensitivity 8 |

The manufacturer defined default value is ```8``` (Sensitivity 8).

This parameter has the configuration ID ```config_12_1``` and is of type ```INTEGER```.


### Parameter 14: Enable/Disable Basic Set Command

The motion Sensor can reverse its value of BASIC SET when motion is triggered

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Disable |
| 1 | Enable |

The manufacturer defined default value is ```0``` (Disable).

This parameter has the configuration ID ```config_14_1``` and is of type ```INTEGER```.


### Parameter 15: value of basic set command



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | send off |
| 1 | send on |

The manufacturer defined default value is ```0``` (send off).

This parameter has the configuration ID ```config_15_1``` and is of type ```INTEGER```.

### Wakeup Interval

The wakeup interval sets the period at which the device will listen for messages from the controller. This is required for battery devices that sleep most of the time in order to conserve battery life. The device will wake up at this interval and send a message to the controller to tell it that it can accept messages - after a few seconds, it will go back to sleep if there is no further communications. 

This setting is defined in *seconds*. It is advisable not to set this interval too short or it could impact battery life. A period of 1 hour (3600 seconds) is suitable in most instances.

Note that this setting does not affect the devices ability to send sensor data, or notification events.

This parameter has the configuration ID ```wakeup_interval``` and is of type ```INTEGER```.

### Wakeup Node

When sleeping devices wake up, they send a notification to a listening device. Normally, this device is the network controller, and normally the controller will set this automatically to its own address.
In the event that the network contains multiple controllers, it may be necessary to configure this to a node that is not the main controller. This is an advanced setting and should not be changed without a full understanding of the impact.

This parameter has the configuration ID ```wakeup_node``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The HKZW_MS01 supports 2 association groups.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.
Reports the motion detection and battery
Reports the motion detection and battery

Association group 1 supports 5 nodes.

### Group 2: Basic Set

assigned to send Basic Set Command

Association group 2 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V5| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V5| Linked to BASIC|
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_FIRMWARE_UPDATE_MD_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_WAKE_UP_V2| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |

### Documentation Links

* [Manual](https://www.opensmarthouse.org/zwavedatabase/675/HKZW-MS01-MANUL.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/675).
