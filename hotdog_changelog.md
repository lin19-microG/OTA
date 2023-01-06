06-01-2023

- ASB Security string 2023-01-05
- microG on 0.2.26.223616-16
- Firewall UI (Settings - Network & Internet - Manage data restrictions)
- Some kernel patches
- French translation for ported features


29-12-2022 - 1st 'official' build

- Port of GrapheneOS' 'Scoped storage' feature


27-12-2022 - INITIAL BUILD (Beta)

- Pre-installed microG 0.2.26.223616-2
- Pre-installed AuroraStore 4.1.1, AuroraDroid and AuroraServices
- OTA Support
- Bromite as default browser, 108.0.5359.156
- Additional security hardening features listed below:
  * Cloudflare as default DNS (instead of Google)
  * Privacy-preferred default settings
  * Optional blocking of Facebook- and Google-Tracking (Settings - Network & Internet)
  * Optional disable captive portal detection or choose provider (default is GrapheneOS and not Google; Settings - Network & Internet)
  * Increased max. password length of 64
  * Enhaced controls for secondary users
  * Secure application spawning
  * No submission of IMSI/phone number to Google when GPS is in use
  * Default hosts file with many blocked ad/tracking sites (can be disabled)
  * Privacy-enhanced Bromite SystemWebView, 108.0.5359.156
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
