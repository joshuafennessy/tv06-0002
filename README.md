# Motion And Tool Configuration

- Stepper X: LDO 2504 AC
- Stepper Y: LDC 2504 AC
- Stepper Z1: Stepper Online NEMA 17
- Stepper Z2: Stepper Online NEMA 17
- Stepper E: LDO Pancake Motor

- Toolhead: StealthBurner with CW2
    - Bondtech IDGA gears
    - Extruder Entry Sensor
    - Toolhead Entry Sensor
    - Filametrix (filament cutter)
- Hotend: Phaetus Rapdio v2 HF PT1000
- Nozzle: TriangleLabs ZS V6 High Flow

# Accessory Configuration

- ECRF v2 (Trianglelabs Kit)
- Cotton-Tail Lite (bufferless with gate sensors)
- RepRack Rewinders
- BentoBox AirFilter

# Hardware Configuration

- Raspberry Pi 4B connected via UART to
- Fystec Spider 3.0
- Critical Aux MCU Boards
  - LDO NighthawkSB (connected via USB/CAN interface)
  - BTT MMB CAN v1.1 (connected via USB)
- Non-critcal Aux MCU boards
  - Beacon Rev H (connected via USB) 

# Software Configuration
- Debian Bookworm
- Kalico (stable)
- Happy-Hare (stable)

# Klipper Add-ons

- Beacon
- KAMP
- Klipper led-effect

# Klipper-Backup 💾 
Klipper backup script for manual or automated GitHub backups 

This backup is provided by [Klipper-Backup](https://github.com/Staubgeborener/klipper-backup).

