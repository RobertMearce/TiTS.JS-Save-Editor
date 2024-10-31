# TiTS.JS-Save-Editor

***This is a reference to modifying the Trials in Tainted Space save game file***

There are two file variants the game can save to: a game-specific *.tits file (by using the "Save File" button) or the more editable *.sol file (by using the "Save" button). This editing guide will only concentrate on the Local Shared Object file type (*.sol).

Editors
There are a couple ways one can go about editing save files.

Game state editor
The Javascript or JS version of TiTs Currently has an unofficial game state editor that allows you to edit the game whilst it is being played. 

TiTS Save Editors

For the JS Version TiTS.JS Save Editor

JS version saves are stored as .jsons, which can be opened by standard text editors and websites. The former often requires some form of plugin to format the text in an easily readable format while websites will often do this automatically. Note that this method of editing is akin to being a power user, you can do MUCH more but only if you know what you are doing.

CourseVector .minerva
The most common and more publicly available method is by using a local shared object editor named .minerva. Legacy versions of .minerva can be downloaded and used on a machine locally, but requires the AIR environment software to be installed for the program function properly. Alternatively, the current online-browser version will allow uploading a *.sol file to edit, then saving the changes to a new file.

Save File Location
Depending on the operating system and/or web browser being used, the *.sol save file generated for the game may be found in one of a number of places.

**[W I N D O W S  7](https://bit.ly/4fhJkOM)**

**[W I N D O W S  8](https://bit.ly/4fhJkOM)**

**[W I N D O W S  10](https://bit.ly/4fhJkOM)**

**[W I N D O W S  11](https://bit.ly/4fhJkOM)**

Save File Anatomy
There are a variety of value types that make up the components of a save file. 

They include:

Integer - A whole (non-decimal) number.

Number - A number with a decimal or fractional value.

Boolean - A binary value consisting of true or false.

String - A sequence of text-based characters.

Array - A collection of variables grouped together.

Object - Similar to an array, a collection consisting of a group of variables.
