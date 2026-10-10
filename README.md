[ [Engligh](README.md) | [日本語](README_ja.md) ]

---

# PC1245-EARTH DEFENDER

<img src="./images/earthdefender.png">

## Overview

This is a program for the “PC-1245” pocket computer, released by Sharp in Japan in 1983. <br>
It consists of BASIC and machine code. <br>

<br>

## How to Play

- Enemies attack from the left and right while you aim at the Earth in the center of the screen.
- Move the Earth Defense Satellite left and right to fire beams and destroy the enemies.
- The enemy will also attack with beams, so use your shield to defend yourself. However, you cannot fire beams while your shield is active.
- Damage increases if the enemy reaches Earth or is hit by a beam attack.
- If your damage reaches 100%, it's game over.

<br>

## Controls

- [4][6] : Move the Earth Defense Satellite Left and Right
- [2] : Fire a beam
- [8] : Use/Disable Shield

<br>

## Transfer to the actual device

Connect the cassette interface to the pocket computer and then connect it to the PC.<br>
After running the load command on the pocket computer, you can load it by playing the following WAV file on the PC.<br>

```
/wav/earthdefender-bas.wav
/wav/earthdefender-bas-C500.wav
```

<br>

## Play on PokecomGo

Please transfer the following two files to your smartphone and load them into the app.

```
/src/earthdefender.bas
/dist/earthdefender-C500.bin
```

<br>

## Play on PC-1251 Emulator

Copy the following file to the `programs` directory in the PC-1251 Emulator installation folder.

```
/src/earthdefender.bas
/dist/earthdefender-C500.bin
```

Add the following line to the top of `/src/earthdefender.bas`.

```
# bin: earthdefender-c500.bin &C500
```

Start the PC-1251 Emulator, and it will run when you select it with [Ctrl]+[O].

<br>

## Author

Hitoshi Iwai (aburi6800)

<br>

## Update History

October 4, 2026, ver. 1.00
- Initial release

October 5, 2026, ver. 1.10
- Minor fixes to screen display

October 6, 2026, ver. 1.11
- bug fixes.

<br>

## Licence

MIT Licence

<br>

## Thanks

- [SC61860 Asembler YASM61860](https://www.oit.ac.jp/labs/rd/rssrv/kobayashi-lab/~yagshi/old_web/misc/pocketcom/yasm.html)
- [Pocket Tools](http://pocket.free.fr/html/soft/pocket-tools_e.html)
- [Genymotion](https://www.genymotion.com/)
- [Pokecom Go](https://digihori.jimdofree.com/index/emulator/)
- [PC-1251 Emulator](https://github.com/woriguchi/pc1251-emulator/tree/main)
