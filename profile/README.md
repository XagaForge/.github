## Xaga Project
<div>
  <img align="right" width="35%" src="https://gsmchina.com/wp-content/themes/xiaomiuiwp/phone_pics/b_poco-x4-gt-7.jpg">
</div>

This organization contains repositories to build AOSP ROMs for POCO X4 GT / Redmi K50i / Redmi Note 11T Pro(+) (xaga) with some extra personal additions and modifications over [xiaomi-mt6895-devs](https://github.com/xiaomi-mt6895-devs) trees. Currently supporting: Android 17 QPR0 (17.0)

### Required device specific repositories
* [**Device Tree (xaga)**](https://github.com/XagaForge/android_device_xiaomi_xaga.git) (`android_device_xiaomi_xaga`)
* [**Device Tree (common)**](https://github.com/XagaForge/android_device_xiaomi_mt6895-common.git) (`android_device_xiaomi_mt6895-common`)
* [**Vendor Tree (xaga)**](https://gitlab.com/ChrisCatto/android_vendor_xiaomi_xaga.git) (`android_vendor_xiaomi_xaga`)
* [**Vendor Tree (common)**](https://github.com/XagaForge/android_vendor_xiaomi_mt6895-common.git) (`android_vendor_xiaomi_mt6895-common`)
* [**Kernel Source**](https://github.com/XagaForge/android_kernel_xiaomi_mt6895.git) (`android_kernel_xiaomi_mt6895`)

### Other required repositories
* [**Mediatek Sepolicy**](https://github.com/XagaForge/android_device_mediatek_sepolicy_vndr.git) (`android_device_mediatek_sepolicy_vndr`)
* [**Mediatek Hardware**](https://github.com/XagaForge/android_hardware_mediatek.git) (`android_hardware_mediatek`)
* [**Xiaomi Hardware**](https://github.com/XagaForge/android_hardware_xiaomi.git) (`android_hardware_xiaomi`)
* [**MiuiCamera**](https://github.com/XagaForge/proprietary_vendor_xiaomi_miuicamera-xaga.git) (`proprietary_vendor_xiaomi_miuicamera-xaga`)

### Optional patch
* [**Return false for GetDeviceLockStatus() if fenrir=true**](https://github.com/XagaForge/android_system_core/commit/ec75c2110708759fdcaf10e9874717e7f60b1fe8) (`android_system_core`)

