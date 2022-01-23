---
codename:beryllium
---

=====================
  23 January 2022
=====================

 * conquerOS 5.1 release
 * Added few missing 64bit blobs
 * Fixed SystemUI misalignment (QQS/QS/Statusbar)
 * Updated perf HAL, stack
 * Vulkan UI Renderer
 * QTI Bluetooth stack
 * Fixed UI Glitches / Flickers
 * Fixed Google Photos unlimited backup @ original quality
 * Removed CAF's ugly unaligned emergency button on lockscreen
 * Added machine learning back gesture
 * Added Separate Wi-Fi & Mobile Data QS tiles
 * Fixed battery stats
 * Fixed nearby sharing
 * Fixed laggy live wallpaper
 * stripped down gapps
 * Added Alarm and Vibrate status bar icons
 * Added scramble Pin and Quick Unlock Pin options
 * Added option to allow tethering via VPN upstream
 * Added Smart Space (at a glance on lockscreen/ambient)
 * Added Google's advanced battery prediction based on Turbo
 * removed AOSP's system update setting from system settings
 * switched to Google's SettingsIntelligenec for suggestions provider
 * switched to Pixel's Google Sans Clock font
 * fixed navbar padding after removing bottom pill
 * monet styled power menu 
 * added adb root

=====================
  25 September 2021
=====================


Source Side Changelog:

 * Bump to 4.7
 * Merged 'LA.QSSI.11.0.r1-13200-qssi.0' CAF Tag
 * Merged August Securoty Patch
 * Allow to hide VPN icons in the statusbar
 ( Some changes for PixelPropUtils to pas SafetyNet
 ( Fix Battery Usage Header layout
 * Limit Keyguard charging stats updates
 * Fix some UI Crashes that really annoying
 * Set OpenGL Skia as default renderer
 * Add proper config for WiFi 5GHz support


Device Side Changelog:
 * Reverted back to Xiaomi PowerHAL
 * Tweaked hints for more battery backup
 * Switch to SilverCore Kernel for now
 * Add QTI Vibration HAL
 * Implement QPNP haptic effects
 * Adjust haptic & vibration patterns
 * Use dex2oat64 for mi845
 * Add and publish Codec2 HAL service
 * Add back FPS Tile from XiaomiParts
 * Update Thermal Profiles
 * Introduce PocoExtras
 * Move PocoExtras & Thermal Profiles to System
 * Update PocoExtras & Thermal Profiles icons
 * Update 
	- Firmware parts from polaris V12.5.1.0
	- Display, Adreno blobs from OP6 RKQ1.201217.002/2106301530
	- WFD from OP6 and LA.QSSI.11.0.r1-12100-qssi.0
	- MSM_IRQBALANCE from OP6 RKQ1.201217.002/2106301530
	- Time Services from OP6 RKQ1.201217.002/2106301530
	- TEE, TUI, PerMgr, ESE from OP6 RKQ1.201217.002/2106301530
	- DRM from OP6 and LA.UM.9.8.r1-02700-SDM710.0
	- VPP and OMX from OP6 RKQ1.201217.002/2106301530
	- Configstore from OP6 RKQ1.201217.002/2106301530
	- Snapdragon CVE from OP6 RKQ1.201217.002/2106301530
	- Widevine from OP6 RKQ1.201217.002/2106301530
	- DPM, IMS, RIL from LA.QSSI.11.0.r1-12100-qssi.0
and LA.UM.9.8.r1-02700-SDM710.0
 * Uprev ESEPowerManager
 * Configure cpusets for dex2oat
 * Build servicetracker HAL from source
 * Kang dexpreopt bits from OnePlus 7 tree
 * Fix VoLTE/Data SIM Slot switching issue
 * Use blueline power profile
 * Boost GPU to max for Expensive Rendering
 * Import Pixel2016Exclusive (Unlimited Photos)
 * Allow thermal-engine to read /sys/devices

=====================
    28 July 2021
=====================
Source Side Changelog:
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

Device Side Changelog:
 - Switch to XDKernel Beta 2.0
 - Fixed HDR bug in Google Photos
 - Tweaked powerhints
 - Force enable iorap
 - Many under the hood improvements.

=====================
    20 June 2021
=====================
 - 4.3 code base release
 - Based on LA.QSSI.11.0.r1-12200-qssi.0 CAF Tag!
 - Redesigned About Phone
 - Redesigned Settings Dashboard
 - Redesigned ConquerOS Features Dashboard
 - Redesigned default Settings preference style.
 - Added ConquerOS Themer
 - Added new ConquerOS wallpaper
 - Added Option to change HW renderer to Vulkan under dev options
 - Added Long Screenshot
 - Added long press power button to enable flashlight
 - Added option to hide lock icon on lockscreen
 - Added 404 IDE, 404 Sammy, and Shapeshift Clock Face
 - Added Oxypink, Oixel Blue, Neon Carrot, and Blueline accent color
 - Show LTE+/4G+ if possible
 - Reduced UI corner roumd radius
 - Improvement for live blur
 - Added new wallpaper
 - Fixed QS Panel glitch on devices with small display/lower resolution
 - Enabled Permission Hub 2.0
 - Added OOS Silent Icon on status bar
 - Now you can prevent Battery Saver from reduce display refresh rate
 - Some improvement for QS Panel detail and UI
 - Some improvement for System Navigation
 - Some Improvement for Package manager
 - Moved Battery Graph to Main Battery Info
 - Under the hood performance improvements
 - Initial Release for POCO F1 
