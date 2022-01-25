# springboardlogo
A great example of how tiny a full screen animation could be on an Apple II 6502 system.  In this example, the entire full screen animation fits in 6,933 bytes.

![Screen Shot](resources/ScreenShot.png?raw=true "Screen Shot")

This animation was developed in 1985 by @dornquast in a rush to have it ready for a new MPG crack.

I had built my own toolchain for graphics, an editor that would allow the creation of binary assets which were then saved as generated source code to be included in the master merlin assembly code.

The program itself is TP.s with the binary created TP.

It can be executed by simply typing `BRUN TP`
