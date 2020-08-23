---
layout: documentation
title: HM-HS1CA - ZWave
---

{% include base.html %}

# HM-HS1CA CO Sensor with acoustic alarm
This describes the Z-Wave device *HM-HS1CA*, manufactured by *[Zipato](http://www.zipato.com/)* with the thing type UID of ```Zipato_hmhs1ca_00_000```.

The device is in the category of *Smoke Detector*, defining Smoke detectors.

![HM-HS1CA product image](https://opensmarthouse.org/assets/zwave/attachments/741/co-sensor-hs1caz.jpg)


The HM-HS1CA supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

The HM-HS1CA does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. Refer to the *Wakeup Information* section below for further information.

## Overview

This product is a Smart Carbon Monoxide Sensor and adopts super low power consumption Z-Wave wireless network technology, used for detecting carbon monoxide. Sensor adopts high performance eloctrochemical sensor, supports sound and flash alarm. It has high stability, super low power consumption, little sensitivity drift and many other features.

### Inclusion Information

 Press the Net_Button 3 times within 1.5s, Green LED is blinking 3 times within 1 second.

### Exclusion Information

 Press the Net_Button 3 times within 1.5s

### Wakeup Information

The HM-HS1CA does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. The wakeup period can be configured in the user interface - it is advisable not to make this too short as it will impact battery life - a reasonable compromise is 1 hour.

The wakeup period does not impact the devices ability to report events or sensor data. The device can be manually woken with a button press on the device as described below - note that triggering a device to send an event is not the same as a wakeup notification, and this will not allow the controller to communicate with the device.


Every 24h by default

## Channels

The following table summarises the channels available for the HM-HS1CA -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Binary Sensor | sensor_binary | sensor_binary |  |  | 
| Alarm (CO) | alarm_co | alarm_co |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |

### Binary Sensor
Channel type information on this channel is not found.

### Alarm (CO)
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.



## Device Configuration

The device has no configuration parameters defined.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The HM-HS1CA supports 3 association groups.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.

Association group 1 supports 1 node.

### Group 2: Group 2

Root Device group(Binary Sensor) Binary Sensor Command Class: Compatible with 300 series 

  1. Binary Sensor reports status of CO or no CO via Lifeline.
  2. When the sensor detects status change of CO and no CO, the device will be triggered.

Association group 2 supports 5 nodes.

### Group 3: Group 3

Root Device group(Notification) 

  1. Notification reports status of detect CO or no CO via Lifeline. 
  2. When the sensor detects status change of CO and no CO, the device will be triggered.

Association group 3 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_SENSOR_BINARY_V2| |
| COMMAND_CLASS_ASSOCIATION_GRP_INFO_V1| |
| COMMAND_CLASS_DEVICE_RESET_LOCALLY_V1| |
| COMMAND_CLASS_ZWAVEPLUS_INFO_V1| |
| COMMAND_CLASS_ALARM_V4| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_WAKE_UP_V2| |
| COMMAND_CLASS_ASSOCIATION_V2| |
| COMMAND_CLASS_VERSION_V2| |

### Documentation Links

* [Manual](https://www.opensmarthouse.org/zwavedatabase/741/hm-hs1ca-z-USER-MANUAL.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/741).
