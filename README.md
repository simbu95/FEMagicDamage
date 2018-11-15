# FEMagicDamage

Prototype of a magic damage calculation curve. The basics is you input your base stats and equipment, and it will create a chart of how likely a character at a certain hp will die. This is currently only setup for Zeromus Un-nerfed Big Bangs. If you generate graphs multiple times, you will get the curves overlayed on top of each other. 

You can also run this in a command window using java -jar, which will allow you to see the raw data points, in case you want to try to plot everything.

Final Detail, the damage is calcualted to a resolution of 50 damage for data simplifcation. This seems fair enough, but can be tweaked if really needed. 
