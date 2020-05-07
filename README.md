# keyboard

I use [QMK](https://github.com/qmk/qmk_firmware).

For the DZ60, I use the keymap dz60/60_ansi_arrow_fkeys.
For the massdrop alt, I use massdrop/alt/default_md

to compile the firmware simply run:
```
cd qmk_firmware
patch -p1 -i ../custom.patch

# for dz60
sudo make dz60:60_ansi_arrow_fkeys:dfu

# for massdrop alt
sudo make massdrop/alt:default_md
sudo mdloader --first --download massdrop_alt_default_md.bin --restart
```
