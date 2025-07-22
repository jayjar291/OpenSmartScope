# OpenSmartScope

OpenSmartScope is an open-source, smart Newtonian telescope based on my [OpenScope MK II](https://www.printables.com/model/290201-openscope-mk-ii-f5-newtonian-telescope) design.

---

##  Project Goals

-  USB-powered, compact, and portable
-  Absolute focusing system using magnetic sensing
-  Guided motorized primary mirror star collimation
-  Integrated flip-style shutter and flat field panel
-  INDI-compatible for full Ekos/KStars automation
---

##  Hardware Overview

| Subsystem              | Description |
|------------------------|-------------|
| **OTA Design**         | Lightweight modular OTA, 3D-printed frame with aluminum extrusions for strangth |
| **Focuser**            | Belt-driven dual-leadscrew focuser, powered by a NEMA 11 stepper with position tracking via Linear Hall effect sensor and magnet. |
| **Primary Collimation**| Three 28BYJ-48 steppers adjust the primary mirror tilt for automated collimation. |
| **Shutter/Flat Panel** | Flip-over style mechanical shutter with integrated flat frame lighting; controlled by a servo and monitored via light sensor. |
| **Controller**         | Raspberry Pi Pico or Pico W handles stepper/servo/light sensor/magnet sensor. |

---


## Software

- **INDI Driver** for:
  - Focuser control (absolute)
  - Primary mirror collimation
  - Shutter & flat field control
  - Sensor feedback
---

##  TODO

- [ ] Complete CAD for focuser assembly
- [ ] Complete CAD for Primary mirror cell
- [ ] Complete CAD for OTA assembly
- [ ] Complete electronic schematics
- [ ] Create firmware for pico
- [ ] Create INDI driver
- [ ] Create Python tools for collimation

---

##  Contributing

Pull requests are welcome! Whether it's firmware, hardware tweaks, STL improvements, or INDI driver development—collaboration is encouraged. Open issues, suggest features, or help me test components.

---
