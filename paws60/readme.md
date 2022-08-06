# Paws60 PCB
 A 60% Multi-Layout Hotswap PCB, designed in KiCAD 6.99. The name was based on Cat and Dog paws.

**This board not have prototyped for Rev 2 yet! Only Rev 1 was been printed and used.**

Renders (KiCAD):
- **Revision 1**:

![image](https://user-images.githubusercontent.com/24840279/182379467-022b089e-da02-421d-9946-defddcf08226.png)

![image](https://user-images.githubusercontent.com/24840279/182379588-39a0dc68-b351-4beb-ba90-1372e7693d11.png)

- **Revision 2**:

![image](https://user-images.githubusercontent.com/24840279/183244382-43863de1-f439-4c8f-95e6-d1d476cc4520.png)

![image](https://user-images.githubusercontent.com/24840279/183244397-e320aee8-4619-461b-b50a-81bbafa8fb04.png)

IRL images:
- **Revision 1**:

![image](https://user-images.githubusercontent.com/24840279/182385132-ce94d258-4f27-4ca6-9ac3-ea53eae76fe1.png)

![image](https://user-images.githubusercontent.com/24840279/182385251-2dc4e824-cbf8-4ff4-8bfc-1be0eb4ebe62.png)

- **Revision 2**:
**Coming soon!**

## Features
**Revision 1**:
- Uses the ATMEGA32U4-AU MCU, with 32KB of internal flash and 1KB of EEPROM
- Uses Kailh Hotswap Sockets
- Multi-layout (see below)
- JST connector for Unified Daughterboard support
- Physical BOOT button for getting into bootloader if [bootmagic](https://github.com/qmk/qmk_firmware/blob/master/docs/feature_bootmagic.md) isn't available. Acessible under PCB.
- SWD header for debugging
- ESD chip (SRV05-4) to prevent damage from electrostatic discharge
- Polyfuse to prevent overcurrent
- Bonus: Curved traces and teardrops

**Revision 2**:
- Uses the RP2040 MCU (new), with 16MB of external flash
- Uses Kailh Hotswap Sockets
- Added anti-shearing to the hotswap sockets
- Holes of hotswap socket holes are plated, you can still solder in a switch, should a hotswap socket ever shear off for whatever reason
- Multi-layout (see below)
- JST connector for Unified Daughterboard support
- Physical BOOT button for getting into bootloader if [bootmagic](https://github.com/qmk/qmk_firmware/blob/master/docs/feature_bootmagic.md) isn't available. Acessible under PCB.
- SWD header for debugging
- ESD chip (SRV05-4) to prevent damage from electrostatic discharge
- Polyfuse to prevent overcurrent
- 2 SK6812 Mini-E LED for Capslock and Esc
- Bonus: Curved traces and teardrops

## Firmware
- **Revision 1**:  
[QMK Firmware](https://github.com/qmk/qmk_firmware/tree/master/keyboards/horrortroll/paws60)  
[QMK Configurator](https://config.qmk.fm/#/horrortroll/paws60/LAYOUT_60_ansi_split_bs_rshift)

- **Revision 2**:
**Coming soon!**

## Multi-Layout Support
- **Revision 1**:

![image](https://user-images.githubusercontent.com/24840279/182381983-1a340809-20dd-4bb4-b09c-02a45d1bae50.png)

- **Revision 2**:

![image](https://user-images.githubusercontent.com/24840279/182387052-c9dd6492-3420-4183-b67f-bb1a35d2cf67.png)
