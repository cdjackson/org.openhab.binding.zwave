---
layout: documentation
title: WTRFID - ZWave
---

{% include base.html %}

# WTRFID Mini Keypad RFID
This describes the Z-Wave device *WTRFID*, manufactured by *Wintop* with the thing type UID of ```Wintop_wtrfid_00_000```.

The device is in the category of *Remote Control*, defining Any portable or hand-held device that controls the status of something, e.g. remote control, keyfob etc..

![WTRFID product image](https://opensmarthouse.org/assets/zwave/attachments/217/WTRFID.jpg)


The WTRFID supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is unable to participate in the routing of data from other devices.

The WTRFID does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. Refer to the *Wakeup Information* section below for further information.

## Overview

Zipato Mini RFID Keypad combines RFID and Z-Wave protocol for access control purposes. The user can identify themselves either by using manual code buttons on the numeric keypad, or by using a RFID key fob. The keypad fully supports Zipato automated security systems but also works with other Z-Wave enabled networks. “Home” and “Away” buttons allow the arming and disarming of security system or running any automation scenario.

### Inclusion Information

 INCLUDE IN Z-WAVE NETWORK

  1. Make sure your Z-Wave controller is in the right operation mode (include or exclude)
  2. Press and hold the tamper for 1 seconds and release to start the inclusion/exclusion process (indication mode: Ready for learn mode).
  3. The product will start NWI automatically after unsuccessful normal inclusion

### Exclusion Information

 EXCLUDE from Z-WAVE NETWORK

  1. Make sure your Z-Wave controller is in the right operation mode (include or exclude)
  2. Press and hold the tamper for 1 seconds and release to start the inclusion/exclusion process (indication mode: Ready for learn mode).
  3. The product will start NWI automatically after unsuccessful normal inclusion

### Wakeup Information

The WTRFID does not permanently listen for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. The wakeup period can be configured in the user interface - it is advisable not to make this too short as it will impact battery life - a reasonable compromise is 1 hour.

The wakeup period does not impact the devices ability to report events or sensor data. The device can be manually woken with a button press on the device as described below - note that triggering a device to send an event is not the same as a wakeup notification, and this will not allow the controller to communicate with the device.


The default value is 0x1C20 = 7200 sec = 2 hour

The default node is 0xFF = 255 (broadcast)

It is possible to send a wake up notification on user interaction. Besides sending a Wake Up Notification automatically every 2 hours (or any other time that is configured using the Wake Up Interval Set command), the Mini Keypad RFiD/Z-Wave also sends a Wake Up Notification when:

  * The tamper alarm state changes (Mini Keypad RFiD/Z-Wave is mounted or removed from the wall)
  * A tag read
  * A code is entered using the keypad

When the wake up time is set to 0 a wake up notification is never send periodically, only on user interaction

## Channels

The following table summarises the channels available for the WTRFID -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|
| Switch | switch_binary | switch_binary |  |  | 
| Alarm (burglar) | alarm_burglar | alarm_burglar |  |  | 
| Alarm (access)  [Deprecated]| notification_access_control | notification_access_control |  |  | 
| Alarm (raw) | alarm_raw | alarm_raw |  |  | 
| Battery Level | battery-level | system.battery_level | Battery | Number |

### Switch
Channel type information on this channel is not found.

### Alarm (burglar)
Channel type information on this channel is not found.

### Alarm (access) [Deprecated]
Event ID 5 = Away

Event ID 6 = Home

Channel type information on this channel is not found.

### Alarm (raw)
Channel type information on this channel is not found.

### Battery Level
Channel type information on this channel is not found.



## Device Configuration

The following table provides a summary of the 5 configuration parameters available in the WTRFID.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Set to Default | Set all configuration values to default values (factory settings). |
| 2 | Audible feedback config | To configure the time the beep is automatically turned off in seconds. |
| 3 | Feedback timeout | Feedback timeout |
| 4 | Feedback beeps per Second | To configure the number of beeps per second. Every beep is fixed about 10ms. |
| 5 | Mode | Configure the operating mode |
|  | Wakeup Interval | Sets the interval at which the device will accept commands from the controller |
|  | Wakeup Node | Sets the node ID of the device to receive the wakeup notifications |

### Parameter 1: Set to Default

Set all configuration values to default values (factory settings).

Values in the range 1 to 255 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 2: Audible feedback config

To configure the time the beep is automatically turned off in seconds.
The Mini Keypad RFiD/Z-Wave supports 3 types of notification sound configurations:

  1. Notification sound disabled (configuration parameter 2 set to zero)
  2. Notification sound enabled (default, configuration parameter 2 set to auto-stop time).
Values in the range 1 to 255 may be set.

The manufacturer defined default value is ```15```.

This parameter has the configuration ID ```config_2_1``` and is of type ```INTEGER```.


### Parameter 3: Feedback timeout

Feedback timeout
To configure the timeout to wait for a WAKEUP\_NO\_MORE_INFORMATION before the error beep is automatically sound. The error beeps are fixed 8 beeps shortly after each other (0 -> disabled)
Values in the range 0 to 255 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_3_1``` and is of type ```INTEGER```.


### Parameter 4: Feedback beeps per Second

To configure the number of beeps per second. Every beep is fixed about 10ms.

Values in the range 1 to 255 may be set.

The manufacturer defined default value is ```2```.

This parameter has the configuration ID ```config_4_1``` and is of type ```INTEGER```.


### Parameter 5: Mode

Configure the operating mode
If any mode other then 3, that value will be reported after a get but will be handled in SW as mode 1.

  * MODE 1: Normal operating mode.
  * MODE 3: Z-Wave chip is always on to request e.g. version or manufacturer id. If any mode other then 3, that value will be reported after a get but will be handled in SW as mode 1.
Values in the range 1 to 255 may be set.

The manufacturer defined default value is ```1```.

This parameter has the configuration ID ```config_5_1``` and is of type ```INTEGER```.

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

The WTRFID supports 1 association group.

### Group 1: Group1


Association group 1 supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| |
| COMMAND_CLASS_USER_CODE_V1| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_ALARM_V2| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_LOCK_V1| |
| COMMAND_CLASS_BATTERY_V1| |
| COMMAND_CLASS_WAKE_UP_V1| |
| COMMAND_CLASS_ASSOCIATION_V1| |
| COMMAND_CLASS_VERSION_V1| |

### Documentation Links

* [Installation Instructions](https://www.opensmarthouse.org/zwavedatabase/217/Zipato-Zwave-RFID-Tag-Reader-Installation.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](https://www.opensmarthouse.org/zwavedatabase/217).
