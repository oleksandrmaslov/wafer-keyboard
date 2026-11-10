# Wafer keyboard

PCB and enclosure sources for the Wafer split keyboard, separated from the
[ZMK firmware repository](https://github.com/oleksandrmaslov/wafer-zmk-config).

- `pcb/`: editable KiCad sources, BOM, production/fabrication files and original backups.
- `case/`: CNC STEP models and the thread drawing.

The hardware-related commit history is retained. The files were verified
byte-for-byte against firmware `main` at `507ab12` before being removed from its
working tree. No PCB or case geometry was modified during the split.

## Licence and use

Copyright (c) 2026 Oleksandr Maslov.

The design files and hardware documentation authored by Oleksandr Maslov use
**[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)**. The full,
unmodified standard text is included in [LICENSE](LICENSE).

| Use | Permission |
| --- | --- |
| Study, share, or modify design files for noncommercial use | Allowed with attribution, a licence link, and notice of changes. |
| Build a keyboard for your own personal use | Allowed, including modified designs. |
| Pay a PCB fabricator or CNC shop for your personal copies | Explicitly allowed. |
| Commercial production, kits, or paid builds for sale | Separate written permission required. |

See [MANUFACTURING.md](MANUFACTURING.md) for the additional personal-fabrication
permission, commercial contact, and third-party rights. Software and firmware
remain under MIT in the separate firmware repository. Historical licence files
remain in Git history; the obsolete duplicate notices were removed from the
current tree.

## CREDITS

### INSPIRATION

Inspired by the [Totem Keyboard](https://github.com/GEIGEIGEIST/TOTEM) and [Mikehive](https://github.com/mikeholscher/zmk-config-mikefive), but with a slimmer profile and magnets for usability. Big thanks to Rasmus for introducing me to the ISP1807.

### HELP FIXING THINGS

People who helped me create this board and fix stuff:

#### PCB
- [Rasmus Koit](https://github.com/rasmuskoit)
- [Eden](https://github.com/galaxyeden)
#### CASE
- [Vlad Vodkin (consulted me to build this case, huge thanks)](https://t.me/vlad30303)

