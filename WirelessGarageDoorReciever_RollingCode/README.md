# Wireless Garage Door Receiver - Rolling Code Security Research

An embedded security research project focused on analyzing, implementing, and evaluating the security mechanisms of wireless garage door receivers utilizing **rolling code (hopping code)** protocols.

---

## ⚠️ Disclaimer
> **Educational and Research Purposes Only:** This repository is published for academic study, security research, and educational awareness. Do not test or target systems without explicit, written legal authorization from the system owners. Unauthorized access to wireless systems is illegal.

---

## 📌 Project Overview
Traditional fixed-code remote controls send an identical binary signal every time a button is pressed, making them trivial to capture and replay using inexpensive hardware. To mitigate this, modern wireless access systems utilize **rolling codes**, where the authentication payload changes dynamically with every transmission using a synchronization counter and a cryptographic block cipher (e.g., KeeLoq).

This project explores:
- How rolling code transmitters and receivers establish and maintain counter synchronization.
- RF signal capture, demodulation, and parsing of wireless frames.
- Implementation/emulation of receiver-side logic to study potential vulnerabilities (such as replay limitations, synchronization windows, and brute-force/desynchronization vulnerabilities).

---

## 🛠️ Hardware & Tools Used
* **Flipper Zero (Momentum Firmware):** Utilized for advanced RF signal capture, analysis, and protocol testing.
* **EEPROM Reader and Programmer:** Used to extract and analyze non-volatile secret data and keys stored in the microcontroller’s EEPROM.
* **Hex Editor Neo:** Employed for viewing, analyzing, and modifying raw binary and hex files.
* **Multimeter:** Used for signal measurement, voltage monitoring, and circuit continuity checks.

---
