# M5PORKCHOP CYD Port Flasher

A browser-based web flasher for installing the **PorkChop CYD Port** onto the **ESP32-2432S028R (Cheap Yellow Display)** without needing to set up Arduino IDE.

This flasher is for the **CYD port of PorkChop** created by **Xombi3**.  
The **firmware/port itself was not made by me** — I built the **web flasher tool** to make installation easier.

> PorkChop CYD Port by [Xombi3](https://github.com/Xombi3/Porkchop-cyd-Port)  
> Original M5PORKCHOP project by 0ct0sec

---

## Flash Tool

<a href="PASTE-YOUR-FLASHER-LINK-HERE" target="_blank" rel="noopener noreferrer">
  <img src="Images/flash-button.png" alt="Flash Now" width="200" height="140">
</a>

Open the flasher in a **Chromium-based browser** such as **Chrome** or **Edge**, connect your CYD board by USB, and follow the prompts.

No Arduino IDE setup is needed when using the web flasher.

---

## What This Flasher Installs

This flasher installs the **PorkChop CYD Port**, a port of **M5PORKCHOP** for the **ESP32-2432S028R (Cheap Yellow Display)**.

PorkChop CYD is a compact WiFi security research tool that brings the PorkChop experience to the CYD touchscreen platform.

### Main Firmware Capabilities

- 802.11 passive scanning
- Deauthentication testing
- WPA handshake capture
- PMKID harvesting
- Wardriving support
- Fake beacon injection
- BLE advertising spam features
- RF spectrum analysis
- SD card save support
- Web Remote support
- XP, leveling, challenges, achievements, and unlockables

---

## Supported Hardware

| Component | Details |
|-----------|---------|
| Board | ESP32-2432S028R ("Cheap Yellow Display") |
| Display | 2.8" 240x320 TFT |
| Touch | Resistive touchscreen |
| Storage | microSD card recommended |
| USB | Used for flashing and power |

---

## Why This Flasher Exists

The original CYD port is flashed through an Arduino-based workflow.  
This project provides a simpler **browser-based flashing option** so users can get the PorkChop CYD firmware onto their board faster and with less setup.

---

## How To Flash

1. Connect your **ESP32-2432S028R** to your computer with a USB data cable.
2. Open the web flasher link above in **Chrome** or **Edge**.
3. Select the correct serial device when prompted.
4. Start the flashing process and wait for it to complete.
5. Reboot the board after flashing if needed.

---

## Notes

- Use a **USB data cable**, not a charge-only cable.
- Chromium-based browsers work best for web serial flashing.
- A **microSD card** is recommended for capture and save features inside the firmware.
- This repo is for the **flasher tool**, not for ongoing firmware development.

---

## Firmware Project

For firmware details, features, setup notes, and original port information, see:

**PorkChop CYD Port:**  
[https://github.com/Xombi3/Porkchop-cyd-Port](https://github.com/Xombi3/Porkchop-cyd-Port)

---

## Credits

| Project | Author |
|---------|--------|
| M5PORKCHOP | 0ct0sec |
| PorkChop CYD Port | Xombi3 |


---

## Disclaimer

This project is provided for educational and authorized security research purposes only.  
Only use it on networks, devices, and environments you own or have explicit permission to test.

---

## License

Please refer to the upstream firmware project for firmware licensing details.  
This repository is primarily for the web flasher and related installer assets.