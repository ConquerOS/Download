=====================
  26 September 2021
=====================
Source Side Changelog:
 * Bump to 4.7
 * Merged 'LA.QSSI.11.0.r1-13200-qssi.0' CAF Tag
 * Merged August Securoty Patch
 * Allow to hide VPN icons in the statusbar
 * Some changes for PixelPropUtils to pas SafetyNet
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
 * Address some sepolicy denials
 * Adjust TASchedtuneBoost for better power consumption
 * Disable EAS on early-init
 * Enable color mode in Setting/Display
 * Enable EAS after boot
 * Fix libperfmgr logspam
 * Set keyguard bottom margin
 * Switch to stock schedtune boost values
 * Update GCamGo to 2.8.392471939_release
 * Change kernel to platinum EAS 4.4.284
 * Kernel build with latest AOSP Clang

=====================
    10 August 2021
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
 - Disable dalvik minidebuginfo generation
 - Disable dexpreopt minidebuginfo
 - Disable KPTI feature
 - Fix some sepolicy denials
 - Move boot animation early start to late-init
 - Optimize everything on preopt
 - overlay: Don't show Mobile plan preference item
 - overlay: Show app info settings memory
 - overlay: Show avatar in settings home screen
 - Strip off some debug packages
 - Use cortex-a73 for arm64
 - Upstream kernel 4.4.279
 - Merge CAF tag LA.UM.9.2.r1-03500-SDMxx0.0
 - Switch to Simple Low Memory Killer
 - Compiler Proton Clang with LTO

=====================
    12 July 2021
=====================
Source Side Changelog:
 - 4.4 Code base release
 - Merged LA.QSSI.11.0.r1-12400.02-qssi.0
 - Redesigned Settings Dashboard UI
 - Allow Hotspot client use VPN upstream
 - Add Native Zygote fork loop
 - OxygenOS 11 QS Panel style
 - Updated prebuilt apps
 - Optimized new jemalloc. 69FPS POOPG. thanks to ProtonAOSP
 - Allow user to unlink notification and ringtone volume
 - Unlimited Photo storage with original quality (Gapps variant only)
 - Fix lock icon drawable
 - Fix some overlay
 - Some other small improvement and optimization

Device Side Changelog:
 - Build minijail service for imsrtpservice
 - Build power stats and label it
 - Disable Bluetooth by default
 - Enable freeform window management
 - Enable VoLTE support for Smartfren (Indonesia)
 - Enable VoLTE support for Telkomsel (Indonesia)
 - Set linker to LLD
 - Switch to Thermal 2.0 mock
 - Update graphics blobs V@0490.0 from taimen RP1A.201005.004
 - Update IMS libs to LA.UM.9.6.2.r1-04100-89xx.0
 - Update lib-imsvtcore from mojito
 - Update org.codeaurora.ims permissions
 - Update portion IMS blobs from LA.UM.9.6.2.r1-02500-89xx.0
 - Update qti-telephony-common from LA.UM.9.6.2.r1-04100-89xx.0
 - Update WFD blobs from phoenix_sprout RKQ1.201123.002
 - Use Userspace LMKD if there's no LMK driver
 - Upstream kernel 4.4.275
 - Merge CAF tag LA.UM.9.2.r1-03400-SDMxx0.0
 - Compiler Proton Clang with LTO

=====================
    17 June 2021
=====================
Source Side Changelog:
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

Device Side Changelog:
 - Addressed selinux denials
 - Enforcing build
 - Fix SIM Settings bugs
 - Remove sys.use_fifo_ui prop
 - Merge 4.4.273 kernel update
 - Merge tag LA.UM.9.2.r1-03300-SDMxx0.0
 - Update wireguard v1.0.20210606

=====================
      01 May 2021
=====================

* Initial Build
