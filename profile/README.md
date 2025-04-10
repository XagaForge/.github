## Xaga Project - Personal extras
<img align="right" width="180" height="180" src="https://camo.githubusercontent.com/5b983921617d1bc2bf4aeb8a47f66d740124e6da8f7399ff82ae4a98a3eb4db2/68747470733a2f2f63646e2e636e626a302e6664732e6170692e6d692d696d672e636f6d2f6232632d73686f706170692d706d732f706d735f313635333338343536382e353639383538382e706e67">

This organization contains repositories to build AOSP ROMs for POCO X4 GT / Redmi K50i / Redmi Note 11T Pro(+) (xaga) with personal additions and modifications over [xiaomi-mt6895-devs](https://github.com/xiaomi-mt6895-devs) trees.

### Repositories
* [**Device Tree (xaga)**](https://github.com/XagaForge/android_device_xiaomi_xaga.git) (`android_device_xiaomi_xaga`)
* [**Device Tree (mt6895)**](https://github.com/XagaForge/android_device_xiaomi_mt6895-common.git) (`android_device_xiaomi_mt6895-common`)
* [**Kernel Tree**](https://github.com/XagaForge/android_kernel_xiaomi_mt6895.git) (`android_kernel_xiaomi_mt6895`)
* [**Vendor Tree (xaga)**](https://gitlab.com/priiii08918/android_vendor_xiaomi_xaga.git) (`android_vendor_xiaomi_xaga`)
* [**Vendor Tree (mt6895)**](https://github.com/XagaForge/android_vendor_xiaomi_mt6895-common.git) (`android_vendor_xiaomi_mt6895-common`)
* [**Mediatek Hardware Tree**](https://github.com/XagaForge/android_hardware_mediatek.git) (`android_hardware_mediatek`)
* [**Xiaomi Hardware Tree**](https://github.com/XagaForge/android_hardware_xiaomi.git) (`android_hardware_xiaomi`)
* [**Firmware Tree**](https://github.com/XagaForge/android_vendor_firmware.git) (`android_vendor_firmware`)
* [**MiuiCamera Tree**](https://gitlab.com/priiii1808/proprietary_vendor_xiaomi_miuicamera-xaga.git) (`proprietary_vendor_xiaomi_miuicamera-xaga`)

The `android_device_mediatek_sepolicy_vndr` repository remains unmodified and can be used directly from the [xiaomi-mt6895-devs](https://github.com/xiaomi-mt6895-devs) organization.


### External patch
* [vendor: Add fastboot packages build](https://github.com/AresOS-UDC/vendor_lineage/commit/19afe7c7e98c9ff5f57c57d09edfa954142e65b6) (Only required if you choose to build fastboot packages using our method)
