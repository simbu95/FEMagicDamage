# FEMagicDamage

You must download the lib folder as well, otherwise it won't work. 

Prototype of a magic damage calculation curve. The basics is you input your base stats and equipment, and it will create a chart of how likely a character at a certain hp will die. The default values of spell might and spell multi are setup for the strongest big bang zeromus can use, but you can edit them for different spells and bosses. 

You can also run this in a command window using java -jar, which will allow you to see the raw data points, in case you want to try to plot everything.

Final Detail, the damage is calcualted to a resolution of 50 damage for data simplifcation. This seems fair enough, but can be tweaked if really needed. 
