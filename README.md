# Bruce Board All-in-One

**Bruce Board All-in-One** is a compact, integrated development board designed to unleash the full power of [[Bruce Firmware](https://github.com/0xbruce/bruce)](https://bruce.computer/) — a flexible and offensive-capable firmware built for ESP32. Whether you're into red teaming, wireless experimentation, or embedded development, this board gives you everything in one place — no breadboards, no wiring, no mess.

![3D_View](https://github.com/user-attachments/assets/a8bf4128-304f-4c34-9406-8a43b343cbd5)


---

## 🔥 Why Bruce Board?

Most ESP32 boards require add-ons, modules, or jumper wires to become useful. Bruce Board is different. It combines the essential hardware required for security testing, IoT control, and custom firmware deployment — all directly on the PCB.

Paired with Bruce Firmware, it becomes a fully-fledged hacking and automation toolkit in your pocket.

---

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
