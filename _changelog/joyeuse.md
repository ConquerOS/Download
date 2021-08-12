---
codename:joyeuse
---
=====================
    11 August 2021
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
 - Address some denial
 - Change kernel to Yuki-Iridium 4.14.238
 - Move perf configs to device tree
 - Some minor improvemnts

=====================
    04 August 2021
=====================
Source Side Changelog:
* Merged LA.QSSI.11.0.r1-12700.01-qssi.0
* Added Android S Clock
* Added Network traffic

Device Side Changelog:
* Drop FM
* Fix some GApps Bootloop for Vanila
* Remove redudent audio configs
* Update LA.UM.9.1.r1-09600-SMxxx0.0 blobs
* Update QTI telephony from LA.QSSI.11.0.r1-10400-qssi.0

=====================
    13 July 2021
=====================
Source Side Changelog:
* 4.4 Code base release
* Merged LA.QSSI.11.0.r1-12400.02-qssi.0
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

Device Side Changelog:
* Add 4MB overhead space to super partition
* Add AIDL Light HAL Support
* Copy c2 google codecs to vendor/etc
* Kill deprecated TARGET_USES_MKE2FS* 

=====================
     20 June 2021
=====================
* User builds
* Update Adreno to QSSI (12100)
* Cleanup thermal-engine
* Update JandaX to Lv.17
* Use cpusets from sunfish

=====================
     13 May 2021
=====================

* Initial release
* SELinux Enforcing
* Spesific build for joyeuse
* Cts pass without Magisk
