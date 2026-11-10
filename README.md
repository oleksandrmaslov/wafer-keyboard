# Wafer keyboard

PCB and enclosure sources for the Wafer split keyboard, separated from the
[ZMK firmware repository](https://github.com/oleksandrmaslov/wafer-zmk-config).

- `pcb/`: editable KiCad sources, BOM, production/fabrication files and original backups.
- `case/`: CNC STEP models and the thread drawing.

The hardware-related commit history is retained. The files were verified
byte-for-byte against firmware `main` at `507ab12` before being removed from its
working tree. No PCB or case geometry was modified during the split.

## Licence

The existing restricted hardware/design licence remains in force; see [LICENSE](LICENSE)
and [LICENSE-HARDWARE.md](LICENSE-HARDWARE.md). The root LICENSE is a copy of the
existing hardware licence. Historical software licence files are retained for
context and apply only to software, which remains in the firmware repository.

A future personal-build/modification grant with separate commercial permission
is under consideration. That proposal has not been adopted; the current licence
still requires written permission for manufacture and modification.

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

