## Xaga Project - Personal extras
<img align="right" width="180" height="180" src="https://cdn.cnbj0.fds.api.mi-img.com/b2c-shopapi-pms/pms_1653384568.5698588.png">

This organization contains repositories to build AOSP ROMs for POCO X4 GT / Redmi K50i / Redmi Note 11T Pro(+) (xaga) with some extra additions and modifications over [xiaomi-mt6895-devs](https://github.com/xiaomi-mt6895-devs) trees. Currently supporting: Android 16 QPR2 (16.2 branches)

### Required device specific repositories
* [**Device Tree (xaga)**](https://github.com/XagaForge/android_device_xiaomi_xaga.git) (`android_device_xiaomi_xaga`)
* [**Device Tree (common)**](https://github.com/XagaForge/android_device_xiaomi_mt6895-common.git) (`android_device_xiaomi_mt6895-common`)
* [**Vendor Tree (xaga)**](https://gitlab.com/priiii08918/android_vendor_xiaomi_xaga.git) (`android_vendor_xiaomi_xaga`)
* [**Vendor Tree (common)**](https://github.com/XagaForge/android_vendor_xiaomi_mt6895-common.git) (`android_vendor_xiaomi_mt6895-common`)
* [**Kernel Sources**](https://github.com/XagaForge/android_kernel_xiaomi_mt6895.git) (`android_kernel_xiaomi_mt6895`)

### Other required repositories
* [**Mediatek Sepolicy**](https://github.com/XagaForge/android_device_mediatek_sepolicy_vndr.git) (`android_device_mediatek_sepolicy_vndr`)
* [**Mediatek Hardware**](https://github.com/XagaForge/android_hardware_mediatek.git) (`android_hardware_mediatek`)
* [**Xiaomi Hardware**](https://github.com/XagaForge/android_hardware_xiaomi.git) (`android_hardware_xiaomi`)
* [**MiuiCamera**](https://gitlab.com/priiii1808/proprietary_vendor_xiaomi_miuicamera-xaga.git) (`proprietary_vendor_xiaomi_miuicamera-xaga`)

### Required patches
* [**Add a stub of TelephonyMetrics**](https://github.com/Nothing-2A/android_hardware_lineage_compat/commit/0d01b8f5594788cb73be6e39e7ed415a30fd5879) (`android_hardware_lineage_compat`)
* [**Whitelist Camera Extensions**](https://github.com/crdroidandroid/android_build_soong/commit/9aba260e31d79c8244a67b6e9b2ceef2e522acb6) (`android_build_soong`)
* [**Whitelist MTK packages**](https://github.com/Nothing-2A/android_build_soong/commit/1d9d22c82c32e207d188a406c61c3d7912ceed31) (`android_build_soong`)

### Optional patch (for fastboot package)
* [**Add fastboot packages build**](https://github.com/AresOS-AOSP/android_vendor_crdroid/commit/1ef13ea2226a38a897e66531ea7f49696808674e) (Requires adaptation depending on the ROM which it is applied on)