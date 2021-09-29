---
codename:ginkgo
---

=====================
   29 September 2021
=====================
Source Side Changelog:
* Bump to 4.7
* Merged 'LA.QSSI.11.0.r1-13200-qssi.0' CAF Tag
* Merged August Security Patch
* Allow to hide VPN icons in the statusbar 
* Some changes for PixelPropUtils to pass SafetyNet 
* Fix Battery Usage Header layout
* Limit Keyguard charging stats updates
* Fix some UI Crashes that really annoying
* Set OpenGL Skia as default renderer
* Add proper config for WiFi 5GHz support

Include 4.6 version update Changelog:
* Use Android 12's FOD Icon
* Fix touch issue on split screen
* Set device name to market name if available
* Use FileChannel#size for APK Sign verification
* Make entityheader transparent
* Add back missing FORCE_STOP_PACKAGES perm to SystemUI
* Added Data usage info on Expanded QS Footer
* Install seccomp filter even if permissive builds
* Sleep when proximity is covered for 3 secs
* Use temporary TwilightState when location is not availavle
* Make Battery icon on QS Panel clickable
* Save and use last fetched location
* Make Guest user avatar follow system accent
* Rework on the Action Buttons looks
* Fixed Option of conquerOS Themer being rested in every reboot
* Added Quick Suggestion section on conquerOS Features menu
* Redesign Battery Info header
* Fix date showing null on Shapeshift Tweleve clock face
* Fix some UI Bugs
* Added bouncy overscroll animation
* Move conquerOS gesture settings to system gesture option
* Follow system accent on SetupWizard
* Fix vdso32 building for 4.19 kernels
* Allow to use boottime as timestamp reference
* Avoid calling getSystemCameraKind if the camera was not mapped yet
* Fix thread safety issues
* Some more minor UI and bug fixes
* New default wallpaper

Device Side Changelog:
* Upstreamed kernel to v4.14.246 (android-4.14-stable)
* Updated MIUI blobs to V12.0.2.0.RCOMIXM
* Fixed random reboots during widevine L1 playback
* Removed widevine firmware hack, R firmware is mandatory
* Boost I/O during bootup to improve boot speed
* Boost CPU during wake for faster faceunlock
* Increased default f2fs checkpoint interval
* Increased hispeed freq for big cluster
* Disabled conservative PL boost
* Reverted AOSP's old VM settings tweaks
* Misc optimizations and fixes in kernel
* Fixed safetynet CTS profile for all
* Added LCD HBM and CABC in XiaomiParts
* Added missing qti_whitelist sysconfig
* Disabled useless cnss-diag service
* Improved schedutil governor ratelimits
* Updated clear speaker audio from MIUI12
* Removed notification and battery LED settings on willow
* Removed TM symbol in kernel name (required by some apps)
* Merged LA.UM.9.11.r1-04700.02 CAF tag in kernel
* Fixed IR sensor
* Enabled idle_state mechanism
* Checkout audio policy config from MIUI Global Stable
* Implemented vibration control under Sound settings

=====================
    11 August 2021
=====================
Source Side Changelog:
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
 - Added SoftAPManager. Now you can block someone who is using your Hotspot
 - Ask lockscreen pass/PIN to use Hotspot, and work mode tile
 - Use Cloudflare DNS
 - Hide sensitive information by default
 - Added Quick PIN Unlock. Phone will be unlocked once you enter correct PIN.
 - Use media artwork as QS Media PLayer Background
 - Some minor UI fixes
 - Some minor improvemnts and fixes

 Device Side Changelog:
- Added vibration control on XiaomiParts
- Added and update some XiaomiParts translation
- Addressed some denials
- Fixed and labeled powerstats hal
- Update QTI telephony jar to LA.QSSI.11.0.r1-12400-qssi.0
- Fixed iorapd not starting
- Enable the pre-rendering feature
- Boosted audio output
- Enabled compile-time CPU specific optimizations
- Updated blobs, GPS HAL, kernel and init scripts to LA.UM.9.11.r1-04500-NICOBAR.0 (CAF)
- Updated MIUI blobs from V12.0.1.0.RCOMIXM
- Upstreamed kernel to v4.14.242
- Fixed random reboots
- Boost GPU to max for blur and disable blur by default
- Increased voice call volume steps to 6
- Freed some RAM from useless virtual framebuffer
- Added offline charging LED indicator
- Removed schedtune boosts to reduce heat
- Undervolt GPU to reduce heat and power draws

=====================
    21 July 2021
=====================
 - Merged LA.QSSI.11.0.r1-12600-qssi.0
 - Allow seamless rotation when PIP enabled
 - Added button to copy crash log to HasteBin
 - Redesigned Power menu glbal action
 - Android S Media Seamless background 
 - Implement SystemUIGoogle from redfin 11 
 - Enable weather on lockscreen date [Gapps] Only
 - Update FOD Indication margin [FOD Devices only]
 - Fix notification overlapping clock faces
 - Added Android S, S DP3, OnePlus Analog Number, Minimal, and Roman
 - Added Google Sans. Manrope, and OnePlus sans fonts
 - Fixed margin for Android S Clock face
 - Use ListPreference instead of Drop down on some settings option
 - Removed shadow under action bar on Light theme
 - Removed unrequired dividers in some sections
 - Use normal preference for BatteryTip
 - 4.4 Code bas release
 - Merged LA.QSSI.11.0.r1-12400.02-qssi.0
 - Redesigned Settings Dashboard UI 
 - Allow Hotspot client use VPN upstream 
 - Add Native Zygote fork loop 
 - OxygenOS 11 QS Panel style
 - Updated prebuilt apps 
 - Optimized new jemalloc. 69FPS POOPG. thanks to ProtonAOSP 
 - Allow user to unlink notification amd ringtone volume 
 - Unlimited Photo storage with original quality (Gapps variant only)
 - Fix lock icon drawable 
 - Fix some overlay 
 - Some other small improvement and optimization 
 - Initial build
