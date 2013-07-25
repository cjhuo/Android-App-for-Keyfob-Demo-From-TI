Android-App-for-TI-s-Keyfob-Demo
================================
This is a demo app modified from the sample code in [Android Samsung BLE APIs Bluez](https://github.com/cjhuo/Android-Samsung-Ble-APIs-Bluez) by my friend Nagaraj Hegde. It is working out of box with demo firmware with name 'keyfobdemo' provided by TI in [CC2540 Mini Development Kit](http://www.ti.com/tool/cc2540dk-mini).

Restrictions
============
1. The app is only working on Samsung's mobile device running with [Android Jelly Bean 4.1.x](http://developer.android.com/about/versions/android-4.1.html).
2. The demo firmware 'keyfobdemo' has to be flashed on your keyfob demo device using TI's BLE stack with version >= 1.2. (version 1.1a doesn't work!!!).
3. Currently only value of axis X is read out and updated on the UI.


Some hints on the application 
=============================

1. Its better to keep the DEFAULT_ENABLE_UPDATE_REQUEST    FALSE, specially if some one is testing more than firmware from CC2540 standpoint. 

2. Its better to completely close the android application before modifying and flashing a new firmware to the CC2540. 
