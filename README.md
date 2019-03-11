# UVCCameraUtility

This is a PoC Android application that uses [saki4510t/UVCCamera](https://github.com/saki4510t/UVCCamera "saki4510t/UVCCamera") library to use an external USB Camera.

This PoC was intended for testing the usage of external USB Cameras on a Raspberry running Android.
Tested on:
* Raspberry 3B
* Android 7.1.2 (Nougat). Ported to Raspberry by [KonstaKANG.com](https://konstakang.com/devices/rpi3/CM14.1/ "KonstaKANG.com")

NOTE: Needs Android NDK 17 or below
Reference the path to the NDK in the local.properties file, next to the SDK path. Ex:

sdk.dir={path}/Android/sdk

ndk.dir={path}/Android/sdk/ndk-bundle
