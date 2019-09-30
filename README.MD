# C64 Magic Desk Cartridge 256kb (SMD version)

This version of the Magic Desk compatible cartridge uses mainly SMD components and supports 28* and 32** pin (E)EPROM and FLASH memory chips **up to 256kB**. The type of memory chip is configured with a solder bridge on the back of the PCB.

The Magic Desk cartridge was originally created by Commodore. Marko Šolajić and Žarko Živanov then utilized the same memory bank switching technique and created the [Magic Desk Cart Generator 2.0](https://csdb.dk/release/?id=132937). ***Please note that the MDCG is now available in version 3.0 and supports up to 1MB memory with slightly different hardware.***

***28-pin:**
M27512, M27C512, AM27C512, W27C512, W27E512, 27SF512, 39SF512 and more

****32-pin:**
M27C2001, M27C1001, NM27C020, NM27C010, AT29C020, AT29C010, 39SF010A, 39SF020A and more

**The MDCG project is available under GNU GENERAL PUBLIC LICENSE.**


## Bill of materials (BOM)

| Name | Component |
|--|--|
| U1 | DIP 28/32 (E)EPROM/FLASH memory (see above) |
| U2 | 74LS02D SO-14 (or HCT) |
| U3 | 74LS174D SO-16 (or HCT) |
| C1-C2 | 100nF 0805 size capacitor |
| R1 | 10k 0805 size resistor |
| S1 | TACT switch (SCHURTER 1301.9303 for instance) |

## PCB Images

![PCB top](https://github.com/anemo78/c64-magic-desk-cartridge-smd-256kb/blob/master/c64-magic-desk-cartridge-smd-256kb--top.png?raw=true)

![PCB bottom](https://github.com/anemo78/c64-magic-desk-cartridge-smd-256kb/blob/master/c64-magic-desk-cartridge-smd-256kb--bottom.png?raw=true)
