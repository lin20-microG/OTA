13-10-2023

- Sec. string 2023-10-05
- Mulch System Webview 118.0.5993.48
- Fixes for CVE-2023-4863 and CVE-2023-5217
- Some kernel patches
- AuroraStore 4.3.2


11-09-2023

- Sec. string 2023-09-05
- Mulch System Webview 117.0.5938.44
- Some kernel patches
- AuroraStore 4.3.1


31-08-2023 - improved interim build 08/23

- Improved battery behavior
- Slightly hardened GPS config
- Removal of some carrier restrictions
- Mulch System Webview 116.0.5845.114
- Dialer patches from CalyxOS offering Signal or WA calls from the Dialer, if available


20-08-2023 - INITIAL BUILD (Productive)

- Fix battery issues
- Based on Firmware F22
- Minor fixes


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
