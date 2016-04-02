# Overview #

No Pain No Game is an Android app that encourages children to become active through reward based incentives. The more active the user is, the more screen time they accumulate. They can enable an outlet in the house by communicating with an application specific web server written in Python that controls home automation hardware. The user's activity is tracked by using the phone's accelerometers as a [pedometer](http://code.google.com/p/pedometer/). Reading information pertaining to exercise and nutrition that is dynamically supplied by an expert in the field also gains the user more screen time.

The intent of this app is to modify the user’s behavior using feedback that is specific to their habits. This requires educating them about nutrition and normal exercise routines, using television and video games as incentives, and also decreasing the overall time spent in front of the television.

# Requirements #

### Android ###
  * SDK Version 7 or newer

### Python ###
  * [Python 2.7](http://www.python.org/download/releases/2.7.1/)
  * [PySerial 2.5](http://pypi.python.org/pypi/pyserial)

### Home Automation Hardware ###
  1. SmartHome [PowerLinc Modem](http://www.smarthome.com/2413S/PowerLinc-Modem-INSTEON-Serial-Interface-Dual-Band/p.aspx)
  1. SmartHome [LampLinc](http://www.smarthome.com/2457D2/LampLinc-INSTEON-Plug-In-Lamp-Dimmer-Module-Dual-Band-2-Pin/p.aspx)

# Installation Instructions #
  1. Download 'NPNG\_server.py' and 'insteon.py' from the Downloads section **(coming soon)**
  1. Download and install [Python 2.7](http://www.python.org/download/releases/2.7.1/) (32-bit version) and [PySerial 2.5](http://pypi.python.org/pypi/pyserial)
  1. In order to use your computer as a home automation server, you'll need to set up a free domain with [DynDNS.com](https://www.dyndns.com/account/services/hosts/add.html). Click on the link and fill out the form according to the following:
    * Hostname should be {username}npng.dyndns-server.com, where {username} is the username you plan on using with the app
    * Leave Wildcard unselected
    * Leave Service Type as "Host With IP Address"
    * Enter your current location's IP Address
    * Leave Mail Routing unselected
    * Under "Remote Access for Devices" select "Home Automation"
    * Click "Add To Cart"
    * Proceed to Checkout (again, this is free)
  1. Plug the SmartHome PowerLinc Modem in and attach the serial cable to your computer
    * Note: this may require a USB to Serial adapter
  1. Plug the SmartHome LampLinc into an outlet of your choosing and plug your television or video game console into the LampLinc
  1. Download the Android application from the Downloads section
  1. Install the app on your mobile device
  1. Ensure your DynDNS is up to date and 'NPNG\_server.py' is running before using


# Screenshots #
https://sites.google.com/site/seanbromage/academics/nopainnogame/NPNG_Login.png?attredirects=0
https://sites.google.com/site/seanbromage/academics/nopainnogame/NPNG_Learn.png?attredirects=0
https://sites.google.com/site/seanbromage/academics/nopainnogame/NPNG_Watch.png?attredirects=0
https://sites.google.com/site/seanbromage/academics/nopainnogame/NPNG_Progress_Steps.png?attredirects=0
