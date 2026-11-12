# Hardware overview

This independent project by **Sidbit08** targets a six-wheeled rover and robotic arm using a Teensy 4.1.

| Subsystem | Design intent | To verify |
| --- | --- | --- |
| Controller | Teensy 4.1 | Firmware, pin mapping and I/O levels |
| Rover drive | 6 motor channels from 12 BTN9970LV half-bridges | H-bridge control, current and thermal limits |
| Alternative drive | 3 Cytron MDD10A dual-channel drivers | Pin assignments and electrical isolation |
| Robotic arm | Actuator and signal interfacing | Joint count, power and connections |
| Power | LM2596 module and XT60/JST connectors | Power-tree protection and connector ratings |
| Other | GPS/serial-labelled connections | Signal levels and device mapping |

The board is not yet manufactured or physically tested.

## References

- [Infineon BTN9970LV datasheet](https://www.infineon.com/assets/row/public/documents/10/49/infineon-btn9970lv-datasheet-en.pdf)
- [Cytron MDD10A](https://my.cytron.io/c-industry/c-dc-motor-drivers/p-10amp-5v-30v-dc-motor-driver-2-channels)
