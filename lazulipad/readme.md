# LazuliPad PCB
 A Numpad Multi-Layout Hotswap Type-C PCB, designed in KiCAD 6.99. The name was based on Lazuli Lapis stones.

**This board not have any prototyped yet!**

Renders (KiCAD):
- **Revision 1**:

![image](https://user-images.githubusercontent.com/24840279/177912575-8265e1b8-8c67-41f9-b6df-4fea375f0d8f.png)

![image](https://user-images.githubusercontent.com/24840279/177912607-92984fd9-9b33-4ff3-b4e6-1130b08aa4a8.png)

## Features
**Revision 1**:
- Uses the AT32F403ACGT7 MCU (new), with 1MB of internal flash and 16MB of external flash
- Uses Kailh Hotswap Sockets
- Added anti-shearing to the hotswap sockets
- Holes of hotswap socket holes are plated, you can still solder in a switch, should a hotswap socket ever shear off for whatever reason
- Multi-layout (see below)
- USB-C connector
- Physical Reset and BOOT0 button for getting into bootloader if [bootmagic](https://github.com/qmk/qmk_firmware/blob/master/docs/feature_bootmagic.md) isn't available. Acessible both of them under PCB.
- SWD header for debugging
- ESD chip (PRTR5V0U2X) to prevent damage from electrostatic discharge
- Polyfuse to prevent overcurrent
- Stabilizer only supported Plate Mount, prevent 90-degree hotswap socket.
- Supported LCD module (ST7789 / 135 X 240).
- Supported 1 Rotary Encoder (EC11)
- Bonus: Curved traces and teardrops

## Firmware
**Coming soon!**

## Multi-Layout Support

![image](https://user-images.githubusercontent.com/24840279/177912701-abb228bd-1fb7-4dc4-8ac3-3bf47eeeb1ba.png)
