# TWRP Tree for Xiaomi 11T
* Brand : Xiaomi
* SoC Vendor : Mediatek
* Chipset : Dimensity 1200
* Implementation : Virtual AB

Spec sheet : https://www.gsmarena.com/xiaomi_11t-11099.php

# What's working
* Everything except vibration

## Quirks
* Uses bootimage for recovery. No recovery partition available.(mka bootimage when building)
* Both of these devices use different keymaster hals - Beanpod for Poco F3 GT and Mitee for K40 Gaming
* Fastboot boot command doesn't work like all xiaomi MTK devices ( This one is no exception)

## Credits
* TWRP devs

## References
* https://github.com/CaptainThrowback/android_device_asus_sm8350-common
* AOSP documentation
