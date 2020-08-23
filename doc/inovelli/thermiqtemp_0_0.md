---
layout: documentation
title: ThermIQ Temperature Sensor - ZWave
---

{% include base.html %}

# ThermIQ Temperature Sensor Ambient Temperature Sensor
This describes the Z-Wave device *ThermIQ Temperature Sensor*, manufactured by *[BeNext](http://www.benext.eu/)* with the thing type UID of ```BeNext_thermiqtemp_00_000```.

The device is in the category of *Sensor*, defining Device used to measure something.

![ThermIQ Temperature Sensor product image](https://opensmarthouse.org/assets/zwave/attachments/1172/DS-Thermostat-cut-spacing-1024x1024-png-110x110-q70.png)


The ThermIQ Temperature Sensor supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

The ThermIQ Temperature Sensor does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. Refer to the *Wakeup Information* section below for further information.

## Overview

Simple ambient temperature sensor that comes with ThermIQ infrared panels

### Inclusion Information

  * Remove the back cover
  * Mount 2 AAA batteries
  * Enable inclusion mode on the controller
  * Press and hold tamper switch till the red led starts blinking
  * Release tamper switch

### Exclusion Information

  * Remove the back cover
  * Mount 2 AAA batteries
  * Enable exclusion mode on the controller
  * Press and hold tamper switch till the red led starts blinking
  * Release tamper switch

### Wakeup Information

The ThermIQ Temperature Sensor does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. The wakeup period can be configured in the user interface - it is advisable not to make this too short as it will impact battery life - a reasonable compromise is 1 hour.

The wakeup period does not impact the devices ability to report events or sensor data. The device can be manually woken with a button press on the device as described below - note that triggering a device to send an event is not the same as a wakeup notification, and this will not allow the controller to communicate with the device.


Device can be set to wake up on a set time interval

### General Usage Information

Typically used in combination with the Resistive High Power Dimmer for an IR Panel that is also delivered by ThermIQ. Set the temperature setpoint with THERMOSTAT\_SETPOINT\_SET and the Thermostat then controls the IR PANEL with BASIC\_ON and BASIC\_OFF. Still searching for specific documentation, adding BeNext config (Dutch) and Resistive High Power Dimmer doc.

## Channels

The following table summarises the channels available for the ThermIQ Temperature Sensor -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Sensor (temperature) | sensor_temperature | sensor_temperature |  |  | 
| Setpoint (heating) | thermostat_setpoint | thermostat_setpoint |  |  | 
| Alarm | alarm_general | alarm_general |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |

### Sensor (temperature)
Channel type information on this channel is not found.

### Setpoint (heating)
Channel type information on this channel is not found.

### Alarm
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.



## Device Configuration

The device has no configuration parameters defined.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The ThermIQ Temperature Sensor supports 1 association group.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.

Association group 1 supports 1 node.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V1| |
| COMMAND_CLASS_THERMOSTAT_SETPOINT_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_WAKE_UP_V1| |
| COMMAND_CLASS_ASSOCIATION_V1| |
| COMMAND_CLASS_VERSION_V1| |

### Documentation Links

* [BeNext environment configuration (NL)](https://www.opensmarthouse.org/zwavedatabase/1172/Hoe-meld-ik-thermostaten-aan---ThermIQ.pdf)
* [Resistive High Power Dimmer EU Quick Start](https://www.opensmarthouse.org/zwavedatabase/1172/ir-paneel-dimmer.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/1172).
