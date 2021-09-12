---
codename:wayne
---
=====================
  12 September 2021
=====================
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

=====================
    08 August 2021
=====================
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
 - Use media artwork as QS Media PLayer Background
 - Some minor UI fixes
 - Some minor improvemnts and fixes

=====================
    29 July 2021
=====================
 - Fixed Android 12 Clock face marginEnd
 - Added NetworkTraffic Meter
 - Enabled Wi-Fi Display Cast
 - Added and enabled Xiaomi Doze
 - Enabled Zygote Preforking for better app loading performance
 - Improve battery backup
 - Some cleanup and improvement on init scripts
 - Some small bug fixes and improvement 

=====================
    21 July 2021
=====================
 - Merged LA.QSSI.11.0.r1-12600-qssi.0
 - Allow seamless rotation when PIP enabled
 - Added button to cpoy crash log to HasteBin
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
 - Initial build
