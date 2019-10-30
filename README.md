Overview
--------

libmodbus is a free software library to send/receive data with a device which
respects the Modbus protocol. This library can use a serial port or an Ethernet
connection.

The functions included in the library have been derived from the Modicon Modbus
Protocol Reference Guide which can be obtained from [www.modbus.org](http://www.modbus.org).

The license of libmodbus is *LGPL v2.1 or later*.

The documentation is available as manual pages (`man libmodbus` to read general
description and list of available functions) or Web pages
[www.libmodbus.org/documentation/](http://libmodbus.org/documentation/). The
documentation is licensed under the Creative Commons Attribution-ShareAlike
License 3.0 (Unported) (<http://creativecommons.org/licenses/by-sa/3.0/>).

The official website is [www.libmodbus.org](http://www.libmodbus.org).

While the library is written in C and designed to run on Linux, Mac OS X, FreeBSD and
QNX and Windows, this repository contains a modified version which allows for FreeRTOS implementation and is tested on ESP32 based IoT device.
