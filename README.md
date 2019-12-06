Litematica Printer
==============
Litematica is a client-side Minecraft mod using LiteLoader.
It is more or less a re-creation of or a substitute for [Schematica](https://minecraft.curseforge.com/projects/schematica),
for players who don't want to have Forge installed.
For compiled builds (= downloads), go to the [releases section](https://github.com/Andrews54757/litematica-printer/releases)

## Printer

The printer feature is like the printer feature from Schematica. In fact, I used their code as reference (credits to them). To use it, just turn on easyPlaceMode and easyPlaceActivationHold and right click hold on a schematic block.

The printer can be configurable with the range_x/y/z configurations. They specify a box, centered at where you click, that will have items placed.

Compiling
=========
* Clone the repository
* Open a command prompt/terminal to the repository directory
* run 'gradlew build'
* The built jar file will be in build/libs/
