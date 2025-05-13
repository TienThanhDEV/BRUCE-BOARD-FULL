# Bruce Board All-in-One

**Bruce Board All-in-One** is a compact, integrated development board designed to unleash the full power of [[Bruce Firmware](https://github.com/0xbruce/bruce)](https://bruce.computer/) — a flexible and offensive-capable firmware built for ESP32. Whether you're into red teaming, wireless experimentation, or embedded development, this board gives you everything in one place — no breadboards, no wiring, no mess.

![3D_View](https://github.com/user-attachments/assets/a8bf4128-304f-4c34-9406-8a43b343cbd5)


---

## 🔥 Why Bruce Board?

Most ESP32 boards require add-ons, modules, or jumper wires to become useful. Bruce Board is different. It combines the essential hardware required for security testing, IoT control, and custom firmware deployment — all directly on the PCB.

Paired with Bruce Firmware, it becomes a fully-fledged hacking and automation toolkit in your pocket.

---
## :computer: List of Features

<details>
  <summary><h2>WiFi</h2></summary>

- [x] Connect to WiFi
- [x] WiFi AP
- [x] Disconnect WiFi
- [x] [WiFi Atks](https://github.com/pr3y/Bruce/wiki/WiFi#wifi-atks)
  - [x] [Beacon Spam](https://github.com/pr3y/Bruce/wiki/WiFi#beacon-spam)
  - [x] [Target Atk](https://github.com/pr3y/Bruce/wiki/WiFi#target-atk)
    - [x] Information
    - [x] Target Deauth
    - [x] EvilPortal + Deauth
  - [x] Deauth Flood (More than one target)
- [x] [Wardriving](https://github.com/pr3y/Bruce/wiki/Wardriving)
- [x] [TelNet](https://github.com/pr3y/Bruce/wiki/WiFi#telnet)
- [x] [SSH](https://github.com/pr3y/Bruce/wiki/WiFi#ssh)
- [x] [RAW Sniffer](https://github.com/pr3y/Bruce/wiki/WiFi#raw-sniffer)
- [x] [TCP Client](https://github.com/pr3y/Bruce/wiki/WiFi#tcp-client)
- [x] [TCP Listener](https://github.com/pr3y/Bruce/wiki/WiFi#tcp-listener)
- [x] [DPWO-ESP32](https://github.com/pr3y/Bruce/wiki/WiFi#dpwo-esp32)
- [x] [Evil Portal](https://github.com/pr3y/Bruce/wiki/WiFi#evil-portal)
- [x] [Scan Hosts](https://github.com/pr3y/Bruce/wiki/WiFi#evil-portal)
- [x] [Wireguard Tunneling](https://github.com/pr3y/Bruce/wiki/WiFi#wireguard-tunneling)
- [x] Brucegotchi
  - [x] Pwnagotchi friend
  - [x] Pwngrid spam faces & names
    - [x] [Optional] DoScreen a very long name and face
    - [x] [Optional] Flood uniq peer identifiers

</details>

<details>
  <summary><h2>BLE</h2></summary>

- [X] [BLE Scan](https://github.com/pr3y/Bruce/wiki/BLE#ble-scan)
- [X] Bad BLE - Run Ducky scripts, similar to [BadUsb](https://github.com/pr3y/Bruce/wiki/Others#badusb)
- [X] BLE Keyboard - Cardputer and T-Deck Only
- [X] iOS Spam
- [X] Windows Spam
- [X] Samsung Spam
- [X] Android Spam
- [X] Spam All
</details>


<details>
  <summary><h2>RF</h2></summary>

- [x] Scan/Copy
- [x] [Custom SubGhz](https://github.com/pr3y/Bruce/wiki/RF#replay-payloads-like-flipper)
- [x] Spectrum
- [x] Jammer Full (sends a full squared wave into output)
- [x] Jammer Intermittent (sends PWM signal into output)
- [x] Config
    - [X] RF TX Pin
    - [X] RF RX Pin
    - [X] RF Module
        - [x] RF433 T/R M5Stack
        - [x] [CC1101 (Sub-Ghz)](https://github.com/pr3y/Bruce/wiki/CC1101)
    - [X] RF Frequency
- [x] Replay
</details>

<details>
  <summary><h2>RFID</h2></summary>

- [x] Read tag
- [x] Read 125kHz
- [x] Clone tag
- [x] Write NDEF records
- [x] Amiibolink
- [x] Chameleon
- [x] Write data
- [x] Erase data
- [x] Save file
- [x] Load file
- [x] Config
    - [X] [RFID Module](https://github.com/pr3y/Bruce/wiki/RFID#supported-modules)
        - [x] PN532
        - [x] PN532Killer
- [ ] Emulate tag
</details>

<details>
  <summary><h2>IR</h2></summary>

- [x] TV-B-Gone
- [x] IR Receiver
- [x] [Custom IR (NEC, NECext, SIRC, SIRC15, SIRC20, Samsung32, RC5, RC5X, RC6)](https://github.com/pr3y/Bruce/wiki/IR#replay-payloads-like-flipper)
- [x] Config
    - [X] Ir TX Pin
    - [X] Ir RX Pin
</details>

<details>
  <summary><h2>FM</h2></summary>

- [x] [Broadcast standard](https://github.com/pr3y/Bruce/wiki/FM#play_or_pause_button-broadcast-standard)
- [x] [Broadcast reserved](https://github.com/pr3y/Bruce/wiki/FM#no_entry_sign-broadcast-rerserved)
- [x] [Broadcast stop](https://github.com/pr3y/Bruce/wiki/FM#stop_button-broadcast-stop)
- [ ] [FM Spectrum](https://github.com/pr3y/Bruce/wiki/FM#ocean-fm-spectrum)
- [ ] [Hijack Traffic Announcements](https://github.com/pr3y/Bruce/wiki/FM#car-hijack-ta)
- [ ] [Config](https://github.com/pr3y/Bruce/wiki/FM#bookmark_tabs-config)
</details>

<details>
  <summary><h2>NRF24</h2></summary>

- [X] [NRF24 Jammer](https://github.com/pr3y/Bruce/wiki/BLE#nrf24-jammer)
- [X] 2.4G Spectrum
- [ ] Mousejack
</details>

<details>
  <summary><h2>Scripts</h2></summary>

- [X] [JavaScript Interpreter](https://github.com/pr3y/Bruce/wiki/Interpreter) [Credits to justinknight93](https://github.com/justinknight93/Doolittle)
</details>

<details>
  <summary><h2>Others</h2></summary>

- [X] Mic Spectrum
- [X] QRCodes
    - [x] Custom
    - [x] PIX (Brazil bank transfer system)
- [x] [SD Card Mngr](https://github.com/pr3y/Bruce/wiki/Others#sd-card-mngr)
    - [x] View image (jpg)
    - [x] File Info
    - [x] [Wigle Upload](https://github.com/pr3y/Bruce/wiki/Wardriving#how-to-upload)
    - [x] Play Audio
    - [x] View File
- [x] [LittleFS Mngr](https://github.com/pr3y/Bruce/wiki/Others#littlefs-mngr)
- [x] [WebUI](https://github.com/pr3y/Bruce/wiki/Others#webui)
    - [x] Server Structure
    - [x] Html
    - [x] SDCard Mngr
    - [x] Spiffs Mngr
- [x] Megalodon
- [x] [BADUsb (New features, LittleFS and SDCard)](https://github.com/pr3y/Bruce/wiki/Others#badusb)
- [x] USB Keyboard - Cardputer and T-Deck Only
- [x] [Openhaystack](https://github.com/pr3y/Bruce/wiki/Others#openhaystack)
- [x] [iButton](https://github.com/pr3y/Bruce/wiki/Others#ibutton)
- [x] [LED Control](https://github.com/pr3y/Bruce/wiki/Others#led-control)
</details>

<details>
  <summary><h2>Clock</h2></summary>

- [X] RTC Support
- [X] NTP time adjust
- [X] Manual adjust
</details>

<details>
  <summary><h2>Connect (ESPNOW)</h2></summary>

- [X] Send File
- [X] Receive File
- [X] Send Commands
- [X] Receive Commands
</details>

<details>
  <summary><h2>Config</h2></summary>

- [x] Brightness
- [x] Dim Time
- [x] Orientation
- [X] UI Color
- [x] Boot Sound on/off
- [x] Clock
- [x] Sleep
- [x] Restart
</details>
## 🧠 What’s Inside – All-in-One Integration

This board was designed from the ground up to include:

- ✅ **ESP32-2432S028R** main module (ESP32-S3 + 2.8” display)
- ✅ **USB-C** port for flashing and power
- ✅ Socket for **NRF24L01+ PA LNA** 2.4GHz module
- ✅ Support for **433MHz RF (TX/RX)** modules
- ✅ **PN532 NFC** module for tag reading and emulation
- ✅ **GPS GY-NEO-6MV2** for location-based tracking
- ✅ **CC1101** for sub-GHz RF communication
- ✅ **OLED display (I2C)** for real-time feedback
- ✅ Built-in **Li-Ion charger (TP4056)** and **boost converter**
- ✅ Full **IR system** (IR LEDs + VS1838B receiver)
- ✅ Logic-level **MOSFET**, switches, resistors
- ✅ Modular support for **FFC/FPC connectors and cables**

All components are laid out neatly to support Bruce Firmware without additional wiring.

---

## 📦 Full Component List (BOM)

| # | Component | Description |
|--:|-----------|-------------|
| 1 | ESP32-2432S028R | Main MCU + Display |
| 2 | RF NRF24L01+ PA LNA | 2.4GHz wireless comms |
| 3 | FS1000A (433MHz TX) | Radio transmitter |
| 4 | XY-MK-5V (433MHz RX) | Radio receiver |
| 5 | PN532 | NFC reader |
| 6 | GY-NEO-6MV2 | GPS module |
| 7 | CC1101 | Sub-GHz RF |
| 8 | TP4056 | Battery charging |
| 9 | Mini DC-DC | 3.7V to 5V boost |
| 10 | 100Ω SMD resistors | x5 |
| 11 | IR LEDs (5mm) | x3 |
| 12 | VS1838B | IR receiver |
| 13 | IRLML6344 | SMD MOSFET |
| 14 | MSS22D18G2 switches | x10 |
| 15 | SS-12D10 switch | 3-position |
| 16 | FFC connectors (12P) | 0.5mm + 1.0mm |
| 17 | FFC/FPC cable | 12P 1.0mm, 6cm |
| 18 | M3 brass standoffs | x4, 25mm |

> ⚙️ The layout supports quick prototyping, direct testing, and real-world deployments.

---

## 🚀 What Can You Do With It?

Bruce Board is your portable cyber-toolkit:

- Run **Wi-Fi deauth attacks**
- Scan and log **BLE devices**
- Read/write **RFID/NFC**
- Visualize data on **OLED/Display**
- Log GPS routes or attach payloads via GPIO
- Deploy **USB HID scripts**
- Use **web UI** hosted by Bruce Firmware

No hardware hacking. No rewiring. Just flash and go.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `3D_View.png` | 3D render of Bruce Board |
| `Front PCB.svg` / `Backside PCB.svg` | PCB layout views |
| `Gerber_BRUCE_PCB_FULL_2025-05-13.zip` | Gerber files for PCB fabrication |
| `HARDWARE COMPONENTS TABLE.pdf` | Official Bill of Materials (BOM) |

---

## 🧑‍💻 Author

**Nguyễn Tiến Thành**  
📘 Facebook: [Nguyễn Tiến Thành](https://www.facebook.com/nguyentienthanhflim/)  
📍 Vietnam | Embedded Hardware Designer | Security Builder

---

## 💖 Support the Project

If you find this project useful, consider supporting its development:

### 🏦 Bank Transfer (Vietnam)
- **Bank**: Techcombank  
- **Account Number**: `1804599999`  
- **Account Name**: `NGUYEN TIEN THANH`

### 💰 Crypto Donation
- **Address**: `0xd16042ec452c4957365924a233383d3b51fae34f`  
- **Network**: BSC (BNB Smart Chain, BEP20)

Your contribution helps fund future hardware and open-source innovation.

---

## 📜 License

Licensed under the **MIT License**. Feel free to use, remix, and share — just give credit where it’s due.

> Built for hackers, makers, and developers — by Nguyễn Tiến Thành 🇻🇳
