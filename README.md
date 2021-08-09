# ThinkStation P340 Tiny (DGPU) OpenCore EFI Folder

Don't forget to update the MLB, SystemSerialNumber and SystemUUID keys in OC/config.plist with [generated ones](https://github.com/corpnewt/GenSMBIOS).

## TODO

* Move to AppleALC with proper layout ID, none of the stock layout-ids for ALC235 with matching vendor and device ID worked (14, 16, 17, 18, 21, 24, 35, 37, 99)
* Support iGPU (should be trivial, but I'm using an F-SKU processor without iGPU)
