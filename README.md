# FEMagicDamage

Main.exe is a modified version of FF4kster that only reads lunar enemy script data, it does not work for regular enemies anymore, and is not part of the magic damage calculator.

You must download the lib folder as well, otherwise it won't work. 

Prototype of a magic damage calculation curve. The basics is you input your base stats and equipment, and it will create a chart of how likely a character at a certain hp will die. This is currently only setup for Zeromus Un-nerfed Big Bangs. If you generate graphs multiple times, you will get the curves overlayed on top of each other. 

You can also run this in a command window using java -jar, which will allow you to see the raw data points, in case you want to try to plot everything.

Final Detail, the damage is calcualted to a resolution of 50 damage for data simplifcation. This seems fair enough, but can be tweaked if really needed. 
