# CanSat Kit — Documentation

Documentation, user manuals and hardware design files for the **CanSat Kit** —
a starter kit for building a CanSat minisatellite and its ground station,
compatible with the requirements of the *CanSats in Europe* competition and the
Polish CanSat competition organised by ESERO-PL.

This repository holds the released documentation for both generations of the kit.


## Repository contents

| Path | Description |
| --- | --- |
| [`CanSatKit v2/`](CanSatKit%20v2) | Documentation for CanSat Kit rev. 2 (current) |
| [`CanSatKit v1/`](CanSatKit%20v1) | Documentation for CanSat Kit rev. 1.x (legacy) |

Each version folder contains:

- **User manual** — kit contents, technical parameters, connector and
  LED maps, power supply, sensors, radio link, Arduino IDE setup, safety and
  correct-use rules.
- **PCB main** — schematic and PCB drawings (PDF) plus 3D models (STEP, full and
  simplified) of the main CanSat / ground-station board.
- **PCB proto** — schematic, PCB drawings and 3D models of the
  prototyping board.

## Using the 3D models

The `.step` files are provided for mechanical integration of the boards into a
CanSat structure. Where both a full and a simplified model exist, prefer the
simplified one for assembly and envelope checks — it is significantly lighter to
load in CAD software.

## Safety

Before using the kit, read the user manual for your kit revision, in particular
the chapter on safety and correct use. Pay attention to the battery handling and radio transmission
rules described there.
