# Snuzzys-Itemcardmaker
A simple tool to generate itemcards for Pen and Paper or similar games from json files. Uses Typst for formatting and a small shell script for batchmaking. 

Currently only works on Linux distributions due to how paths are called.

"cards" will contain json files containing the cards information. An example and template is provided as "example.json."

"images" will contain icons for the cards. Currently only .svg and .png have been tested but other datatypse should also work.

"items" will contain any rendered cards as pngs. If the user wants a pdf or different format this can be changed in "cardbuilder.sh" by changing the output variable.
