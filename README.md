# Stone Leather Blade
An over-produced rock, paper, scissors 8-bit video game for the [Commander X16](https://www.commanderx16.com/) retro computer.

![SLB Screenshot 1](./gameplay_sm.jpg)

## Run the game in the browser
Click on the "Try It Now" link from [this page](https://cx16forum.com/forum/viewtopic.php?t=7994) to play the game in the browser.

## Run the game locally
Run the game on X16 hardware or [local emulator](https://github.com/X16Community/x16-emulator/releases/tag/r47) (tested on R47).
Within the X16 file system, navigate to the file directory and enter:
```
BOOT
```
This command uses the 'AUTOBOOT.x16' file. If this doesn't work, load the program file:
```
/SLB.PRG
```
then RUN the loaded program:
```
RUN
```

## Source code
Open the file [SLB.TXT](./SLB.TXT) to analyze the pre-compiled X16 BASIC source code. The syntax is formatted specifically for the [BASLOAD compiler](https://github.com/stefan-b-jakobsson/basload-rom/blob/master/README.md). The compiler outputs the SLB.PRG file as tokenized BASIC code.

## Soundtrack
Composed by Crisps. [Listen on Youtube](https://youtu.be/paAPXD5II4s?si=JJ_p_WyMJKwKPGI3)

## License
See the [license file](./license.md)