# Hackintosh Monterey Lifebook E556 EFI 

## ⚠️ Disclaimer
This guide is only for the Fujitsu Lifebook E556. I am NOT responsible for any Damage to your device. Do at your own risk.

> [!IMPORTANT]
> Intel WiFi with Airportitlwm is only for MacOS Monterey.

&nbsp;

## 💻 Tested devices
Some users have reported that similar ThinkPads are compatible with this OpenCore configuration. Here is a list of these devices:

- Fujitsu Lifebook E556

## Introduction

<details>
<summary><strong>💻 My Hardware</strong></summary>
<br>
These are the Hardware component I use. But this OpenCore configuation <strong>should still work</strong> with your device, even if the components are not equal.

Check the model of your WiFi & Bluetooth card. Intel cards should be compatible with itlwm (or AirportItlwm). If your card is from another manufacturer, please check if your card supports macOS. macOS Sonoma no longer supports Broadcom Wifi cards.

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core i3-6100U 2.30GHz          |
| GPU       | Intel UHD Graphics 620               |
| SSD       | Intenso 120GB SSD                    |
| Memory    | 8GB DDR4 2400Mhz                     |
| Camera    | 720p Camera                          |
| WiFi & BT | Intel Wifi & Bluetooth               |

</details>  

</details>

&nbsp;

## Status

<details>  
<summary><strong>✅ What's working</strong></summary>
</br>
 
- [X] Intel WiFi & Bluetooth (thanks to [AirportItlwm](https://github.com/OpenIntelWireless/itlwm))
- [X] Volume Control
- [X] Battery Information
- [X] Audio (Audio Jack & Speaker)
- [X] USB Ports & Built-in Camera
- [X] Graphics Acceleration
- [X] Trackpoint / Touchpad
- [X] Power management / Sleep
- [X] FaceTime / iMessage (iServices)
- [X] Automatic OS updates
- [X] Handoff / Universal Clipboard
- [X] SIP / FireVault 2

</details>

<details>  
<summary><strong>⚠️ What's not working</strong></summary>
</br>


- [ ] AirDrop & Continuity 
  - Only devices with Intel WiFi affected
- [ ] Second Display output (VGA)
- [ ] Sidecar 

</details>

<details>  
<summary><strong>🔄 Not tested</strong></summary>
</br>

- [ ] Displayport Output

</details>

&nbsp;



























This guide will help you to install macOS Monterey on your Fujitsu Lifebook E556.


