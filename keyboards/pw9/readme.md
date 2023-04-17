# pw9

![pw9](imgur.com image replace me!)

*A short description of the keyboard/project*

* Keyboard Maintainer: [Polarity Works](https://github.com/PolarityWorks)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make pw9:default

Flashing example for this keyboard:

    make pw9:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical boot button**: Hold down the button on the back of the PCB and connect to USB, it should show up as a USB drive titled RPI-RP2
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
