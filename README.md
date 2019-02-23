# Quake1-HeadGrenadeGun

## What it does:
Makes the grenade launcher fire gibbed heads instead of grenades (also reduces the re-fire delay).

Demo: https://imgur.com/a/AyWevq3


## How to use it:
Make a "HeadGrenadeGun" directory in your Quake1 directory, put the "PROGS.DAT" file in the directory, and launch the game with:
```
quake.exe -game HeadGrenadeGun
```

Then fire the grenade launcher :)

## How to compile it
* download QuakeC Compiler (QCC) from https://github.com/id-Software/Quake-Tools/tree/master/qcc
* download this repo's "src" directory
* run DOSBox and mounted both paths, and in the "src" directory and run:
```
<path_to_qcc>\qccdos.exe
```
