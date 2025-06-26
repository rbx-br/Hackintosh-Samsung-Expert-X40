# Hackintosh Samsung Expert X40 - 270E-NP270E5K
### Generate your own SMBIOS, recommended MacBookPro16,1

Compatible symbios with macOS Tahoe. But without graphic acceleration until OCLP update comes out

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
![11](https://github.com/user-attachments/assets/add96347-e7e3-46ac-ac8d-1c72434e7a44) ***macOS Big Sur 11.7.10***


![12](https://github.com/user-attachments/assets/60c761ef-7e99-4b7f-a6da-b11ddf1c8af3) ***macOS Monterey 12.7.6***


![13](https://github.com/user-attachments/assets/3b7f23da-3c5d-4906-b9cb-5228d66f1ad0) ***macOS Ventura 13.7.6***


![14](https://github.com/user-attachments/assets/83a3c216-8af2-400c-8914-d9f9bd1fb7df) ***macOS Sonoma 14.7.6***


![15](https://github.com/user-attachments/assets/432a5c91-6c1b-4098-b58f-90c6f2ed9dc5) ***macOS Sequoia 15.5***

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
(***<img width="20" alt="20" src="https://github.com/user-attachments/assets/add96347-e7e3-46ac-ac8d-1c72434e7a44"> Works up to Big Sur***)

NVIDIA GeForce 920M ***(Disabled because it is incompatible with macOS)***
#
![Samsung X40 screen](https://github.com/user-attachments/assets/bcf32d14-799f-4a5d-b8ea-a5671b690fef)
