---
layout: documentation
title: ZSMOKE - ZWave
---

{% include base.html %}

# ZSMOKE Smoke Alarm
This describes the Z-Wave device *ZSMOKE*, manufactured by *BRK Brands, Inc.* with the thing type UID of ```BRK Brands, Inc._zsmoke_00_000```.

The device is in the category of *Smoke Detector*, defining Smoke detectors.

![ZSMOKE product image](https://opensmarthouse.org/assets/zwave/attachments/239/zsmoke.png)


The ZSMOKE supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

The ZSMOKE does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. Refer to the *Wakeup Information* section below for further information.

## Overview

A smart home can also be a safe home. With the First Alert Smoke Detector (ZSMOKE)  you will be immediately notified at the first sign of smoke. The First Alert Smoke Detector is a Z-Wave device that emits a loud alarm when smoke is detected.

### Inclusion Information

  1. Open the battery tray
  2. Hold the Test button while re-inserting the battery tray
  3. When the device beeps, release the button

### Exclusion Information

  1. Open the battery tray
  2. Hold the Test button while re-inserting the battery tray
  3. When the device beeps, release the button

### Wakeup Information

The ZSMOKE does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. The wakeup period can be configured in the user interface - it is advisable not to make this too short as it will impact battery life - a reasonable compromise is 1 hour.

The wakeup period does not impact the devices ability to report events or sensor data. The device can be manually woken with a button press on the device as described below - note that triggering a device to send an event is not the same as a wakeup notification, and this will not allow the controller to communicate with the device.

### General Usage Information

Factory Reset:

  1. Make sure the device is powered
  2. Press and hold the test button for 10+ seconds

## Channels

The following table summarises the channels available for the ZSMOKE -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Alarm | alarm_general | alarm_general |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |

### Alarm
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 1 configuration parameters available in the ZSMOKE.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Send double alarms | Causes the device to send double alarm messages |

### Parameter 1: Send double alarms

Causes the device to send double alarm messages

The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Single Alarm |
| 1 | Double Alarm |

The manufacturer defined default value is ```0``` (Single Alarm).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The ZSMOKE supports 1 association group.

### Group 1: Group 1


Association group 1 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V1| Linked to BASIC|
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_ASSOCIATION_V1| |
| COMMAND_CLASS_VERSION_V1| |

### Documentation Links

* [Manual](https://www.opensmarthouse.org/zwavedatabase/239/FirstAlertSmoke-Manual.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/239).
