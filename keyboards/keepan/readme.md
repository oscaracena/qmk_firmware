# keepan

![keepan](imgur.com image replace me!)

A key panel with buttons, pots, toggles, encoders, sliders and LEDs, all to assist you in playing Elite Dangerous.

* Keyboard Maintainer: [Oscar Aceña](https://github.com/oscaracena)
* Hardware Supported: Custom made
* Hardware Availability: Not yet

Make example for this keyboard (after setting up your build environment):

    make keepan:default

Flashing example for this keyboard:

    make keepan:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
