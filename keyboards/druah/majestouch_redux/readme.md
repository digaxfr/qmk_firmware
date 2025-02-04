# Majestouch Redux

![PCB](https://i.imgur.com/LjoywMI.png)

A replacement PCB for the FILCO Majestouch TKL line of keyboards (and other keyboards) compatible with [Phantom TKL](https://deskthority.net/wiki/Phantom) PCB spacing

* Keyboard Maintainer: [Druah](https://github.com/Druah)
* Hardware Supported: Majestouch Redux
* Hardware Availability: Private buy

Make example for this keyboard (after setting up your build environment):

    make druah/majestouch_redux:default

Flashing example for this keyboard:

    make druah/majestouch_redux:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (the Escape/top left key) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB labelled with "RESET"
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
