# keyboard

I use [QMK](https://qmk.fm/), or on windows [QMK MSYS](https://msys.qmk.fm/).

## Copy config
Copy the keymaps to the installed `qmk_firmware` path:
```
cp -r keyboards/* /PATH/TO/qmk_firmware/keyboards 
```

## Compiling

### dz60
To compile for the dz60, run:
```
qmk flash -kb dz60 -km nick
```
Once the bootloader program is running plug the dz60 in while holding `SPACE + B`.

### id80
To compile for the id80, run:
```
qmk flash -kb idobao/id80/v2/ansi -km nick
```
Once the bootloader program is running press the bootloader button on the underside of the PCB.
