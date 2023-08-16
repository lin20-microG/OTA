16-08-2023 - INITIAL BUILD (Beta)

- Pre-installed microG 0.2.28.231657
- Pre-installed AuroraStore 4.2.5, AuroraDroid 1.0.8 and AuroraServices 1.1.1
- OTA Support
- AOSP Sec. string 2023-08-05
- Based on Firmware F20
- Additional security hardening features listed below:
  * Cloudflare as default DNS (instead of Google)
  * Privacy-preferred default settings
  * Optional blocking of Facebook- and Google-Tracking (Settings - Network & Internet)
  * Optional disable captive portal detection or choose provider (Settinngs - Network & Internet)
  * Increased max. password length of 64
  * Enhaced controls for secondary users
  * Secure application spawning
  * No submission of IMSI/phone number to Google when GPS is in use
  * Default hosts file with many blocked ad/tracking sites (can be disabled)
  * Privacy-enhanced Mulch SystemWebView, 116.0.5845.78
  * Extra control of sensor access for additionally installed user apps (Special access under app permissions)
  * Kernel kept up to date with ASB and other patches
  * Debloated Oneplus blobs (removed Soter and and Google hotword recognition)
  * Hardened bionic lib and constified JNI method tables
  * Optional timeout for Bluetooth and WLAN connections
  * Optional auto-reboot if device not unlocked for defined timeframe 
  * Per connection WiFi randomization option
  * Sensitive QS Tiles require unlocking
  * Native debugging
  * Ability to disable non-system apps from the "App info" screen
  * Firewall UI (Settings - Privacy - Manage data restrictions
  * Scoped storage per app
  * Scoped contacts per app
