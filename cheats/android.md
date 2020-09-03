# Android Debug Bridge (adb)

% android, device, adb, bridge

## Get property
adb -s <device> shell getprop <property>

## Install APK
adb -s <device> install -r <path>

## Uninstall package
adb -s <device> uninstall -r <package>

## Clear user data for package
adb -s <device> shell pm clear <package>

## Dispatch a deep-link / open URI
adb -s <device> shell am start <uri>