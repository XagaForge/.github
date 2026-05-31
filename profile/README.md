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
* [**MiuiCamera**](https://github.com/XagaForge/proprietary_vendor_xiaomi_miuicamera-xaga.git) (`proprietary_vendor_xiaomi_miuicamera-xaga`)

### Required patches
* [**Add xiaomi packages to the whitelist**](https://github.com/XagaForge/android_build_soong/commit/fd57a35469af2616f6378bc53516c8c648215f91) (`android_build_soong`)
* [**Whitelist Camera Extensions**](https://github.com/XagaForge/android_build_soong/commit/dcf3f8a9e601cd4cc220984e8b3c402f143aa843) (`android_build_soong`)

### Optional patch (for fastboot package)
* [**Add fastboot packages build**](https://github.com/AresOS-AOSP/android_vendor_crdroid/commit/1ef13ea2226a38a897e66531ea7f49696808674e) (Requires adaptation depending on the ROM which it is applied on)