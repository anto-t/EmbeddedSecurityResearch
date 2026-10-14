# Embedded Security Research

Hands-on hardware security research and teardown documentation for consumer and embedded devices — covering hardware reverse engineering, firmware extraction, RF/wireless protocol analysis, and storage device internals.

Each project folder documents a specific device: the hardware inspected, the tools and methodology used, and the findings, backed by photos, logs, datasheets, and captured data.

## Projects

### 🔑 [Wireless Garage Door Receiver — Rolling Code](./WirelessGarageDoorReciever_RollingCode)
RF signal capture and analysis of a 433.92 MHz ASK rolling-code garage door transmitter/receiver pair using a Flipper Zero and EEPROM programming tools. Documents the hardware teardown, captured RF data, and general vulnerability notes for this class of rolling-code systems.

### 📡 [TP-Link Router](./TPLinkRouter)
UART-based access and flash memory extraction on a TP-Link router, including serial console logs and a full flash dump.

### 🔧 [WD HDD Board Analysis](./WD_HDD_BoardAnalysis)
Teardown and analysis of a Western Digital hard drive's logic board, including the USB-to-SATA bridge controller and its encryption implementation. Includes board photography and the bridge controller's datasheet.

## Tools & Techniques

- UART / serial console access
- Flash memory reading and extraction
- RF signal capture and analysis (Flipper Zero, SDR)
- EEPROM reading/programming
- PCB-level hardware teardown and component identification

## Disclaimer

This research is conducted on personally owned hardware for educational purposes. It is intended to document reverse-engineering methodology and findings for the embedded security community, not to provide step-by-step attack instructions.

---

*Maintained by [anto-t](https://github.com/anto-t)*

