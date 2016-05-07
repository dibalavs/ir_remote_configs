# ir_remote_configs
configuration files for IR remote controllers

this is example of config file for LG remote controller (NEC protocol) created for Perfect Player on android.
config file was created for ODROID-C1 board.

To use this config please:
adb remount
adb push system/etc/remote.conf /system/etc/
adb shell remotecfg /system/etc/remote.conf
