android-linux-usb-vendor-ids-config
===================================

Disclaimer
----------
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY;  
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  

Installation
------------
1. Copy `51-android.rules` file to `/etc/udev/rules.d/`  
2. Edit `51-android.rules` file to enable each vendor  
3. Make execute `chmod 444 /etc/udev/rules.d/51-android.rules`  

Reference: [__Android.com - Setting up a device for development__](http://developer.android.com/tools/device.html#setting-up)  


LICENSE
-------
See file [__LICENSE__](../master/LICENSE) for details.  