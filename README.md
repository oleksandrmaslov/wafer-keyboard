# Wafer keyboard

A 36-key wireless split keyboard built around a custom PCB and a thin aluminium
case. This repository contains the KiCad sources, fabrication files, and CNC
case models. [ZMK firmware lives separately](https://github.com/oleksandrmaslov/wafer-zmk-config).

![Both halves of the Wafer keyboard](assets/wafer-both-halves.webp)

[Project page, more photos & design story](https://oleksandrmaslov.github.io/portfolio/Wafer.html)
· [Firmware](https://github.com/oleksandrmaslov/wafer-zmk-config)
· [Personal builds & commercial permission](MANUFACTURING.md)

## Hardware

| Specification | Details |
| --- | --- |
| Layout | 36 keys; 18 per half |
| Switches | Kailh PG1316S ultra-thin butterfly switches |
| Controller | ISP1807 SiP with nRF52840 and integrated antenna |
| Power | nPM1300 PMIC; 250 mAh LiPo per half |
| Displays | One nice!view memory LCD per half |
| Enclosure | Machined aluminium; 4–8 mm profile depending on location; magnets |
| Tools | KiCad, Ergogen, and Fusion 360 |

**Status: working prototype.** Electronics and firmware work. The enclosure has
been manufactured, but fit and manufacturing tolerances are still being refined.
The fabrication files here belong to that prototype revision.

## Design and manufacturing files

| Files | Location |
| --- | --- |
| Schematics | [Main](pcb/wafer_keyboard_v3.kicad_sch), [right](pcb/wafer_keyboard_right.kicad_sch) |
| PCB layouts | [Board](pcb/wafer_keyboard_v3.kicad_pcb), [production variant](pcb/wafer_keyboard_v3_production.kicad_pcb) |
| Assembly data | [BOM](pcb/jlcpcb/production_files/BOM-wafer_keyboard_v3_production.csv), [component placement](pcb/jlcpcb/production_files/CPL-wafer_keyboard_v3_production.csv) |
| Fabrication output | [Gerber archive](pcb/jlcpcb/production_files/GERBER-wafer_keyboard_v3_production.zip), [individual files](pcb/jlcpcb/gerber/) |
| CNC case models | [Left](case/wafer_case_left.step), [right](case/wafer_case_right.step) |
| Thread drawing | [PDF](case/Wafer%20threads%20drawing.pdf) |

Original manufacturing outputs and design backups are retained alongside the
editable sources. The original hardware history was preserved when this
repository was separated from the firmware.

## Prototype photos

<p>
  <img src="assets/wafer-assembly.webp" alt="Wafer assembly with the switch frames and exposed electronics" width="49%">
  <img src="assets/wafer-aluminium-case.webp" alt="The machined aluminium enclosure viewed from its USB-C edge" width="49%">
</p>

## Licence and use

The design files, hardware documentation, and photographs authored by Oleksandr
Maslov use **[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)**.
The unmodified standard text is included in [LICENSE](LICENSE).

| Use | Permission |
| --- | --- |
| Study, share, or modify design files for noncommercial use | Allowed with attribution, a licence link, and notice of changes |
| Build a keyboard for your own personal use | Allowed, including modified designs |
| Pay a PCB fabricator or CNC shop for your personal copies | Explicitly allowed |
| Commercial production, kits, or paid builds for sale | Separate written permission required |

See [MANUFACTURING.md](MANUFACTURING.md) for personal-fabrication permission and
commercial contact, and [photo sources](assets/README.md) for image attribution.
Third-party material keeps its own applicable terms; firmware remains under MIT
in its own repository. Historical licence grants remain valid.

Copyright © 2026 Oleksandr Maslov.

## Credits

Inspired by [TOTEM](https://github.com/GEIGEIGEIST/TOTEM) and
[Mikefive](https://github.com/mikeholscher/zmk-config-mikefive).
PCB help: [Rasmus Koit](https://github.com/rasmuskoit) and
[Eden](https://github.com/galaxyeden). Case consultation:
[Vlad Vodkin](https://t.me/vlad30303).
