# DC-DC Buck Converter – KiCad PCB Design

A compact and efficient **DC-DC Buck Converter** designed using **KiCad EDA** for schematic capture and PCB layout. This project converts higher DC input voltage into a stable lower DC output with improved efficiency compared to linear regulators.

The design includes voltage regulation, filtering, feedback control, and status indication circuits suitable for embedded systems, IoT applications, battery-powered devices, and electronics prototyping.

---

## Project Overview

This project demonstrates the design and implementation of a **Buck Converter PCB** using:

* Schematic Design in KiCad
* PCB Layout Design
* 3D PCB Visualization
* Power Regulation Circuit
* Adjustable Output Voltage

The converter is designed for efficient DC voltage step-down applications.

---

# Features

* Adjustable DC output voltage
* Compact PCB layout
* High-efficiency switching regulation
* LED power indication
* Feedback-based voltage control
* 3D PCB design included
* Designed using KiCad

---

# Software Used

* KiCad

Official Website: [KiCad Official Website](https://www.kicad.org?utm_source=chatgpt.com)

---

# Hardware Components

| Component      | Description               |
| -------------- | ------------------------- |
| XL4015         | DC-DC Buck Converter IC   |
| 78L05          | 5V Voltage Regulator      |
| LM358          | Operational Amplifier     |
| Schottky Diode | Fast switching diode      |
| Inductor       | Energy storage component  |
| Capacitors     | Input/Output filtering    |
| Potentiometer  | Output voltage adjustment |
| LEDs           | Status indicators         |

---

# Project Structure

```bash id="53r1kx"
BUCK-CONVERTER/
│
├── Schematic/
│   └── buck_converter.kicad_sch
│
├── PCB/
│   └── buck_converter.kicad_pcb
│
├── Gerber/
│   └── Manufacturing_Files
│
├── Images/
│   ├── BUCK_CONVERTER_3D.png
│   ├── BUCK_CONVERTER_PCB.png
│   └── BUCK_CONVERTER_SCHEMATIC.png
│
└── README.md
```

---

# Circuit Description

The circuit is based on the **XL4015 buck converter IC**, which performs efficient voltage step-down conversion.

## Working Principle

1. DC input voltage is supplied to the converter.
2. XL4015 switches the input at high frequency.
3. Inductor and capacitor filter the switching waveform.
4. Schottky diode improves efficiency and protects the circuit.
5. Feedback network regulates the output voltage.
6. LM358 comparator section provides monitoring and indication.

---

# PCB Design

The PCB was designed with:

* Optimized power trace routing
* Compact component placement
* Proper grounding
* Heat management considerations
* Easy soldering access
* Single-board integrated design

---


# Electrical Specifications

| Parameter         | Value                |
| ----------------- | -------------------- |
| Converter Type    | DC-DC Buck Converter |
| Main IC           | XL4015               |
| Input Voltage     | 8V – 36V DC          |
| Adjustable Output | Yes                  |
| PCB Tool          | KiCad                |
| Regulation Type   | Switching            |

---

# Applications

* Embedded Systems
* IoT Devices
* Battery Charging Systems
* Robotics
* Portable Electronics
* Microcontroller Power Supply
* DIY Electronics Projects

---


# Output Voltage Adjustment

The output voltage can be adjusted using the onboard potentiometer:

* Rotate clockwise → Increase voltage
* Rotate counterclockwise → Decrease voltage

Do not exceed component voltage ratings.

---

# Future Improvements

* Add current limiting protection
* Add thermal shutdown circuit
* Add digital voltage display
* Improve EMI filtering
* Add USB-C power output



This project is open-source and available under the MIT License.
