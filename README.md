# Hackintosh Samsung Expert X40 - 270E-NP270E5K
### Generate your own SMBIOS, recommended MacBookPro16,1

Compatible SMBIOS with macOS Tahoe. But without graphic acceleration until OCLP update comes out

![Samsung X40](https://github.com/user-attachments/assets/30740f5d-7c4e-4ea5-b315-48432d42fc3d)

## Basic description:
Intel® Core™ i7-5500U - Broadwell

RAM 8GB LPDDR3 *(soldered on the motherboard)*

Intel® HD Graphics 5500 - 2GB

Nvidia® GeForce™ 920M 2GB - ***Disabled***

Qualcomm® Atheros™ AR9565 _Wi-FI_ + AR3012 _Bluetooth_ *(soldered on the motherboard)*

Realtek® RTL8105E

Wildcat Point-LP High Definition Audio Controller - based on Realtek® ALC282

Bluetooth BCM92046MD - ***(Internal USB MOD)***

Wi-Fi USB TPLINK® TL-WN725N

## This EFI can boot
![11](https://github.com/user-attachments/assets/492bf142-3e84-4bb3-9ff2-e6d08679e6a7) ***macOS Big Sur 11.7.10***


![12](https://github.com/user-attachments/assets/8772e7c3-cf53-4849-9d5e-c489f8fd36ea) ***macOS Monterey 12.7.6***


![13](https://github.com/user-attachments/assets/8a7caf06-b55b-4b15-a7c1-3756526d2404) ***macOS Ventura 13.7.7***


![14](https://github.com/user-attachments/assets/c0764b86-eb06-48f9-8934-67c5ffa7d377) ***macOS Sonoma 14.7.7***


![15](https://github.com/user-attachments/assets/9974bfe2-522c-408a-b045-0a17b377eb8d) ***macOS Sequoia 15.6***



### It may work on older versions of macOS with another SMBIOS, but has not been tested.


# ✅ Working

Battery life indicator

Intel Graphics HD 5500 ***(Needs OCLP to work)***

Sound internal and external

Keyboard

Touchpad ***(up to 3 fingers gestures. IDK if it's a bug, hardware issue or limitation)***

Webcam

SD Card reader

Screen brightness control

Ethernet

HDMI / VGA

iServices

# ❌ Not working

Internal WiFi - almost useless ***(Needs OCLP to work)*** ***(~15Mbps on 802.11b / ~25Mbps on 802.11g / ~1Mbps on 802.11n)***
Unfortunately, this board has extremely limited support from Mojave onwards and since it is soldered there is not much that can be done. It is necessary to change the PHY mode on the router to 802.11g.

Internal Bluetooth 
(***<img width="20" alt="20" src="https://github.com/user-attachments/assets/492bf142-3e84-4bb3-9ff2-e6d08679e6a7"> Works up to Big Sur***)

NVIDIA GeForce 920M ***(Disabled because it is incompatible with macOS)***
#
![Samsung X40 screen](https://github.com/user-attachments/assets/bcf32d14-799f-4a5d-b8ea-a5671b690fef)
