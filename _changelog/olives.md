=====================
   04 October 2021
=====================

Device Side Changelog:
* Rebased and cleaned up tree
* Merge tag LA.UM.8.6.2.r1-09500-89xx.0 into Display, Media, & Audio HALs
* Update libsdm-color from PAN_sprout RKQ1.200928.002
* Fixed GPS can't lock location
* Soft reboot issue should been fixed

=====================
  23 September 2021
=====================

Device Side Changelog:
* Import PowerHAL from LA.UM.9.6.3.r1-04500-89xx.0
* Import QTI Perf component from AOSPA
* Add MIUI Camera
* Revert Enable sys.use_fifo_ui prop if EAS is present
* Disable surfaceflinger backpressure
* Build QTI Thermal HIDL
* Drop dummy libqti-perfd-client
* WifiOverlay: Disable 5GHz option


=====================
  12 September 2021
=====================

Source Side Changelog:
 * Bump to 4.6
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
 * Kang SF phase offsets from coral
 * Create dummy libqti-perfd-client
 * Kang scheduler settings from sunfish
 * Drop QTI Vibration
 * Update QTI telephony jar to QSSI 12400

Kernel Side Changelog:
 * Disable UClamp & CPU Input boost
 * Switch back to SchedTune
 * Enable SchedTune Assist
 * Increase SLMK minfree a bit


=====================
   11 September 2021
=====================

Source Side Changelog:
* 4.5 Code base release
* Added Russian translation
* Use wallpaper color on Android 12 Clock
* Fixes on Android 12 Clock
* Use normal font just like real Android 12 Clock
* Grant suspend permission for Super Battery Saver
* Added OxygenOS Icon Pack
* Added Shapshift's Android Tweleve Clock
* AppLock: Fix biometric prompt disappearing if app launched from resolver
* fonts: Fix reference to Noto Sans Javanese
* Reworked Panel and change icons
* QS Header item reorder
* Add OOS Volume icons
* Rework QS Drag handle
* Disbale blur screen off animation
* Added SoftAPManager. Now you can block someone who is using your Hotspot
* Ask lockscreen pass/PIN to use Hotspot, and work mode tile
* Use Cloudflare DNS
* Hide sensitive information by default
* Added Quick PIN Unlock. Phone will be unlocked once you enter correct PIN.
* Use media artwork as QS Media PLayer Background
* Some minor UI fixes
* Some minor improvemnts and fixes
* Fixed Lockscreen Wallpaper
* July Security Patch

Device Side Changelog:
* Initial Official build
* Update fingerprint to Redfin September
* SiLonT as default kernel
* Enable freeform windows
* Drop ro.surface_flinger.force_hwc_copy_for_virtual_displays
* Update qti telephony from LA.QSSI.11.0.r1-10400-qssi.0
* Enable qti-telephony-common injection
* Revert force triple frame buffers
* Use OpenGL for HWUI rendering
* Make the UI smoother
* Enable the pre-rendering feature 
* Optimize build specifically for cortex-a53
* Enable adaptive sleep
* Increase charging temperature thresholds
* Add libbeluga.so
