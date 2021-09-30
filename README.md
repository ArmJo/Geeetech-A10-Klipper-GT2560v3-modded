# Geeetech A10 Klipper configuration with GT2560v3 and Mods

I use:
- [Klipper](https://www.klipper3d.org/) on [MainsailOS](https://docs.mainsail.xyz/setup/mainsail-os).
- Geeetech A10 with [GT2560 v3](https://github.com/Geeetech3D/Diagram/blob/master/GT2560_V3.0_SCH.pdf)
- TMC2209 driver in UART
- BLTouch (no clone)
- E3D clone hotend

**Filament runout sensor is not used**

Based on the work of [GusBricker](https://github.com/GusBricker/GeeetechA10_Klipper)

## Features

- TMC2209 in UART mode ([Tutorial](https://github.com/Jonas2903/Geeetech-A10-TMC2209-UART))
- BLTouch
- Exhaust fan and chamber temperature ([Tutorial](https://github.com/Jonas2903/Geeetech-A10-Exhaust-Fan))
- Bigtreetech mini12864 display ([Tutorial](https://github.com/Jonas2903/Geeetech-A10-Display-Mini12864))

I moved from Marlin and my previous config can be found [here](https://github.com/Jonas2903/Marlin-Geeetech-A10-TMC2209-UART-BLTouch) (no display implemented!)

## Planned

- Input shaping with [resonance measurement](https://www.klipper3d.org/Measuring_Resonances.html)
- LED control (Maybe)
