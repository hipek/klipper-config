# Klipper Printer Configs

Klipper firmware configs for multiple 3D printers. Private repo.

## Printers

| Printer | Config | Board |
|---|---|---|
| Anycubic i3 Mega | `printer-ai3m.cfg` | AVR atmega2560 |
| Hevo (custom Voron-style) | `printer-hevo.cfg` | — |
| MKS SGENL v2.0 | `printer-mks-sgenl-v20.cfg` | — |
| MKS SGENL | `printer-mks-sgenl.cfg` | — |
| SKR 1.3 | `printer-skr13.cfg` | — |

**Moonraker:** `moonraker-ai3m.conf`, `moonraker-hevo.conf`

## Hevo2 Configs (`hevo2-configs/`)

Split modular configs for Hevo 2 build:

| File | Purpose |
|---|---|
| `fluidd.cfg` | Fluidd UI panels |
| `mainsail.cfg` | Mainsail UI panels |
| `macros.cfg` | G-code macros |
| `homing.cfg` | Homing overrides/safe Z |
| `speed.cfg` | Speed/accel limits |
| `adxl.cfg` | ADXL345 accelerometer (input shaper) |
| `KAMP_Settings.cfg` | Klipper Adaptive Mesh & Purge |
| `gab-3d-utilities.cfg` | Utility macros (GAB's) |
| `shell_command.cfg` | Shell commands |
| `board_pins.cfg` | Pin assignments |

## Git — 60 commits

Notable changes:
- i3 Mega: sensor type fixes, PID tuning, fan changes
- Hevo: rail upgrade, probe + bed mesh, EBB CAN addition
- Hevo2: split configs, microstep/virtual endstop fixes

Remote: `git@github.com:hipek/klipper-config.git`
