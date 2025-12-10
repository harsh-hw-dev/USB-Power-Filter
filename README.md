# 🔌 USB Power Filter – Designed by Harsh

This repository contains the complete **schematic and PCB design of a USB 5V Power Filter** developed to suppress **noise, ripple, EMI, and transient disturbances** commonly present in USB power lines. The design ensures **clean and stable power delivery** for sensitive embedded, analog, and communication circuits.

---

## ⚡ Key Features

- USB 5V input with EMI/RFI filtering  
- Ferrite bead + multi-stage LC filtering  
- Common-mode choke for noise suppression  
- Transient and ripple attenuation  
- Stable filtered VCC output  
- Dedicated GND separation and noise control  
- Compact footprint for embedded systems  

---

## 🧩 Functional Block Overview

### 1. USB Input Stage
- USB connector with VBUS, D+, D–, GND  
- VBUS passes through a ferrite bead (FB1)  
- Input decoupling capacitor for noise suppression  

### 2. First LC Filtering Stage
- Bulk and ceramic capacitors for ripple smoothing  
- Primary noise reduction before isolation  

### 3. Noise Isolation Stage
- Common-mode choke (L2)  
- Blocks conducted EMI and high-frequency noise  

### 4. Final LC Output Filter
- Series inductor (L1)  
- Output bulk and bypass capacitors  
- Delivers clean filtered VCC  

### 5. Output Interface
- JST connector for filtered VCC and GND output  
- Multiple ground pins for low-impedance return path  

---

## 📊 Electrical Specifications

| Parameter         | Value            |
|-------------------|------------------|
| Input Voltage     | 5V (USB)         |
| Output Voltage    | Filtered 5V      |
| Filtering Type    | Ferrite + LC + CMC |
| EMI Suppression   | High             |
| Ripple Attenuation| Multi-stage     |
| Connector Type    | USB + JST Header |

---

## 🛠 Applications

- Microcontroller boards  
- IoT & RF modules  
- USB-powered development boards  
- Precision analog circuits  
- Communication modules  
- Noise-sensitive sensors  

---

## 📁 Repository Structure

```
/Schematic
/PCB_Layout
/Gerber_Files
/BOM
/3D_View
```

---

## 🎯 Design Objective

To eliminate USB power noise problems such as:
- Switching ripple  
- EMI injection  
- Ground bounce  
- High-frequency interference  

And provide **lab-grade clean 5V power** for sensitive electronics.

---

## 👨‍💻 Designed By

**Harsh**  
Hardware Design Engineer  
Specialized in:
- Power Electronics  
- EVSE & BMS  
- PCB Design & EMI Optimization  
- High-Speed & Mixed-Signal Boards  

---

⭐ If you find this project useful, consider giving it a star!
