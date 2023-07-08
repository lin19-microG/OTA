08-07-2023

- ASB Security string 2023-07-05
- Some kernel patches
- Mulch Webview 114.0.5735.196


08-06-2023

- ASB Security string 2023-06-05
- Some kernel patches
- Mulch Webview 114.0.5735.61
- microG on 0.2.28.231657-5
- FakeStore 0.2.0
- AuroraStore 4.2.3


09-05-2023

- ASB Security string 2023-05-05
- Some kernel patches
- Mulch Webview 113.0.5672.77


13-04-2023

- ASB Security string 2023-04-05
- Some kernel patches
- Removed Bromite browser and shipped LineageOS' Jelly instead
- Mulch Webview 112.0.5615.48


19-03-2023

- ASB Security string 2023-03-05
- Some kernel patches
- Vendor blobs and sec. patch updated from HD1913_11.F.20
- Bromite Webview replaced by Mulch Webview 111.0.5563.58


12-02-2023

- ASB Security string 2023-02-05
- microG on 0.2.27.223616-3
- Firewall UI moved to Privacy Dashboard
- Some kernel patches
- Spoof apps installed by G*PlayStore


06-01-2023

- ASB Security string 2023-01-05
- Bromite Browser and Webview updated to 108.0.5359.156
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
