# altwingducky

AltWingDucky is an extension of the duckyscript format

https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript


Added functionality:
CHAR [0-9]

CHAR is used for sending ALT + Numpad keys

ducky2awd converts STRING commands in a ducky script file to CHAR commands
it also only uses combinations that will not be affected by NUMLOCK status i.e. numpad keys 0,1,3,5,7,9

Usefull in combination with patched version of jackit

Original: https://github.com/insecurityofthings/jackit

Patched: https://github.com/Shiniyoukai/jackit/tree/patch-2
