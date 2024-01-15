# MoErgo Glove80 Custom Configuration for ZMK

![MoErgo Logo](moergo_logo.png)

This repo is Elizabeths personal ZMK configuration of the MoErgo Glove80 wireless split contoured keyboard

## Basic Design

Trying to avoid using home row mods as those seem fairly tedious to get working correctly finding what the correct timeouts are
Not having any keypresses that are in a position that is hard for me to reach, which is very different than most other keyboards
Doing as much hold on the thumb clusters as possible

## Editing

To ease editing I am using Nicks [gui bot](https://nickcoutsos.github.io/keymap-editor/)

## Firmware Files
To locate your firmware files and reflash your Glove80...
1. log into GitHub and navigate to your personal config repository you just uploaded your keymap changes to.
2. Click "Actions" in the main navigation, and in the left navigation click the "Build" link.
3. Select the desired workflow run in the centre area of the page (based on date and time of the build you wish to use). You can also start a new build from this page by clicking the "Run workflow" button.
4. After clicking the desired workflow run, you should be presented with a section at the bottom of the page called "Artifacts". This section contains the results of your build, in a file called "glove80.uf2"
5. Download the glove80.uf2
6. Flash the firmware to Glove80 according to the user documentation on the official Glove80 Glove80 Support website (linked above)

Your keyboard is now ready to use.
