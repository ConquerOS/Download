---
codename:vayu
---

=====================
    6 September 2021
=====================

Device Side Changelog:
- Fixed broken refresh rate after unlocking the device
- Fixed 90hz lagging
- Drop unused prebuilt 64bit audio HAL
- Implement Clear Speaker
- Disable CPU hotplug data parsing on mi_thermald
- Using Chaldea Kernel (Compile with latest Proton Clang)
- Kang SF phase offsets from coral
- Fixed stuttering when opening apps
- Import missing keylayout

=====================
    13 August 2021
=====================

Source Side Changelog:
- 4.5 Code base release
- Merged LA.QSSI.11.0.r1-12700.01-qssi.0
- Added Russian translation
- Use wallpaper color on Android 12 Clock
- Fixes on Android 12 Clock
- Use normal font just like real Android 12 Clock
- Grant suspend permission for Super Battery Saver
- Added OxygenOS Icon Pack
- Added Shapshift's Android Tweleve Clock
- AppLock: Fix biometric prompt disappearing if app launched from resolver
- fonts: Fix reference to Noto Sans Javanese 
- Reworked Panel and change icons
- QS Header item reorder
- Add OOS Volume icons
- Rework QS Drag handle
- Disbale blur screen off animation
- Added SoftAPManager. Now you can block someone used your Hotspot
- Ask lockscreen pass/PIN to use Hotspot, and work mode tile
- Use Cloudflare DNS
- Hide sensitive information by default
- Added Quick PIN Unlock. Phone will be unlocked once you enter correct PIN.
- Use media artwork as QS Media Player Background
- Some minor UI fixes
- Some minor improvemnts and fixes

Device Side Changelog:
- Revise init schedtune configuration
- Align boot and runtime fs tuning to coral
- Set new dm device runtime readahead to 128
- Move device-mapper tuning into init.qcom.rc
- Using Chaldea Kernel (Compile with latest Proton Clang)
- Opt-out Wifi-RTT feature
- Address more denials
- Force srgb over dcip3
- Fixed refresh rate junk (Always set different values for min and max)
- Extract blobs from MIUI V12.5.3.0.RJUINXM

=====================
    2 August 2021
=====================

Device Side Changelog:
* Adapt CAF Power for vayu
* Configure zram from separate fstab
* Revert Migrate to media codecs c2
* Create Adreno symlinks
* Disable the usage of ConfigStore
* Adress more denials
* Using Chaldea Kernel (Compile with latest Clang Proton)
* Lots of improvement on kernel
* Remove virtual framebuffer
* Properly label /sys/kernel/qvr_external_sensor/fd

=====================
    28 July 2021
=====================

Source Side Changelog:
* 4.4 Code base release
- Merged LA.QSSI.11.0.r1-12600-qssi.0
* Redesigned Settings Dashboard UI
* Allow Hotspot client use VPN upstream
* Add Native Zygote fork loop
* OxygenOS 11 QS Panel style
* Updated prebuilt apps
* Optimized new jemalloc. 69FPS POOPG. thanks to ProtonAOSP
* Allow user to unlink notification and ringtone volume
* Unlimited Photo storage with original quality (Gapps variant only)
* Fix lock icon drawable
* Fix some overlay
* Some other small improvement and optimization
- Removed shadow under actionbar on light theme
- Some small UI improvemnts and cleanups
- Added OxygenOS Syle Birghtness slider under Display Settings

Device Side Changelog:
* Initial Official  Build
