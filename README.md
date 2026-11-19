[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/mgc_stm32g4) ![Build](https://github.com/0x007e/mgc_stm32g4/actions/workflows/release.yml/badge.svg) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `MGC_module` - STM32G4

The `STM32G4` (`mgc_module`) is an adaptable board for the [MeGARCard](https://github.com/0x007e/mgc). The board offers the possibility to control the `MeGARCard` with an [STM32G4](#additional-information). The board itself is connected to the `MeGARCard` within the pcb-to-pcb connectors (no soldering necessary). With the onboard dip-switches the board voltage can be regulated from `3V3` to `5V`. Also the usage of hardware-/software-`twi` to control the [SSD1306](#additional-information)-display on the megacard can be selected.

> To mount the board on the `MeGARCard` disconnect the power source (`USB-C` connector) or any other used source from the MeGARCard!

| Experience  | Level                                                                               |
|:------------|:-----------------------------------------------------------------------------------:|
| Soldering   | ![?%](https://progress-bar.xyz/60?progress_color=0000ff&suffix=%20Medium&width=120) |

# Downloads

| Type      | File                                                                                                                                                 | Description     |
|:---------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------|
| Schematic | [pdf](https://github.com/0x007E/mgc_stm32g4/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/30728/main/files)                   | Schematic files |
| Board     | [pdf](https://github.com/0x007E/mgc_stm32g4/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/30728/main/files)                         | Board file      |
| Drill     | [pdf](https://github.com/0x007E/mgc_stm32g4/releases/latest/download/drill.pdf)                                                                              | Drill file      |
| BoM | [xlsx](https://github.com/0x007E/mgc_stm32g4/releases/latest/download/bom.xlsx) / [html](https://github.com/0x007E/mgc_stm32g4/releases/latest/download/ibom.html)          | Bill of Material as Excel/interactive HTML |
| PCB    | [zip](https://github.com/0x007E/mgc_stm32g4/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/mgc_stm32g4/releases/latest/download/kicad.tar.gz)    | KiCAD/Gerber/BoM/Drill files       |

# Hardware

The pcb is created with `KiCAD`. All files are built with `github actions` so that they are ready for a production environment.

## PCB

The circuit board is populated on both sides (Top, Bottom). The best way for soldering the `SMD` components is within a vapor phase soldering system and for the `THT` components with a standard soldering system.

### Top Layer

![Top Layer](https://github.com/0x007E/mgc_stm32g4/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/mgc_stm32g4/releases/latest/download/bottom.kicad.png)

# Additional Information

| Type       | Link               | Description              |
|:----------:|:------------------:|:-------------------------|
| STM32G4  | [pdf](https://www.st.com/resource/en/datasheet/stm32g491cc.pdf) | Arm® Cortex®-M4 32-bit MCU+FPU, 170 MHz / 213 DMIPS |
| SSD1306 | [pdf](https://www.vishay.com/docs/37902/oled128o064dbpp3n00000.pdf) | 128 x 64 Graphic OLED |

---
