# keyboard

the QMK layout I use is found [here](https://github.com/qmk/qmk_firmware/tree/master/keyboards/dz60).

I use the keymap 60_ansi_arrow_fkeys and apply a small patch to the keymap.c file. That file can be found in this repo.

to compile the firmware simply run:
```
patch qmk_firmware/keyboards/dz60/keymaps/60_ansi_arrow_fkeys/keymap.c custom.patch
cd qmk_firmware
sudo make dz60:60_ansi_arrow_fkeys:dfu
```
