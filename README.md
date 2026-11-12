# Teensy Teleops Board

A custom **Teensy 4.1-based PCB** designed by **[Sidbit08](https://github.com/Sidbit08)** to control a **six-wheeled rover** and interface with its **robotic arm**.

## Features

- **6 direct DC motor channels** using 12 × **BTN9970LV** half-bridge drivers (two per motor).
- Alternative drive control through **3 × Cytron MDD10A** dual-channel motor drivers (6 motor channels total).
- Robotic-arm interfacing (actuator details and pin mapping to be verified).
- Teensy 4.1 controller, LM2596 power-module footprint, and power/signal connectors.

## Design Files

| Files / folder | Contents |
| --- | --- |
| `teensy teleops board.kicad_pro` | KiCad project |
| `teensy teleops board.kicad_sch` | Schematic |
| `teensy teleops board.kicad_pcb` | PCB layout |
| `BTN9970/`, `TEENSY_4.1/` | Component libraries and models |
| `TeensyTeleopsGerber/` | Gerber and PTH/NPTH drill files |
| `docs/` | Hardware, fabrication and validation notes |

## Getting Started

1. Install [KiCad](https://www.kicad.org/).
2. Open `teensy teleops board.kicad_pro`.
3. Check component library paths, schematic and PCB layout before fabrication.

## References

- [BTN9970LV — Official Infineon Datasheet (PDF)](https://www.infineon.com/assets/row/public/documents/10/49/infineon-btn9970lv-datasheet-en.pdf)
- [Cytron MDD10A — Product Specifications](https://my.cytron.io/c-industry/c-dc-motor-drivers/p-10amp-5v-30v-dc-motor-driver-2-channels)

## Author & License

Developed by **[Sidbit08](https://github.com/Sidbit08)**. **All rights reserved.** No open-source license is currently granted.
