# Overview

No Pain No Game is an Android app that encourages children to become active through reward based incentives. The more active the user is, the more screen time they accumulate. They can enable an outlet in the house by communicating with an application specific web server written in Python that controls home automation hardware. The user's activity is tracked by using the phone's accelerometers as a [http://code.google.com/p/pedometer/ pedometer]. Reading information pertaining to exercise and nutrition that is dynamically supplied by an expert in the field also gains the user more screen time.

The intent of this app is to modify the user’s behavior using feedback that is specific to their habits. This requires educating them about nutrition and normal exercise routines, using television and video games as incentives, and also decreasing the overall time spent in front of the television.

# Requirements

## Android
 1. SDK Version 7 or newer

## Python
 1. [http://www.python.org/download/releases/2.7.1/ Python 2.7]
 2. [http://pypi.python.org/pypi/pyserial PySerial 2.5]

## Home Automation Hardware
 1. SmartHome [PowerLinc Modem](http://www.smarthome.com/2413S/PowerLinc-Modem-INSTEON-Serial-Interface-Dual-Band/p.aspx)
 2. SmartHome [LampLinc](http://www.smarthome.com/2457D2/LampLinc-INSTEON-Plug-In-Lamp-Dimmer-Module-Dual-Band-2-Pin/p.aspx)