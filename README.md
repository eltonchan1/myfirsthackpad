# myfirsthackpad

image

myfirsthackpad is a space themed 3 key macropad with 5 SK6812 MINI-E LEDs.

It is used as a media playback controller to go back, pause, and go next.

## Features:

- 3 Keys
- 5 SK6812 MINI-E LEDs (3 for underglow and 2 that just glow)

## CAD Model:
Everything fits together using 5 M3 Bolts and heatset inserts. 4 for the case, one for the PCB. 

It has 2 separate printed pieces: the base where the PCB sits, and the top cover. 

image

This was made in Onshape.

## PCB
This is my PCB made in KiCad. The silkscreen was imported from my drawings on photoshop.

Schematic:
image

PCB:
image

## Firmware Overview
This hackpad uses [QMK](https://qmk.fm/) firmware for everything. 

- The 4 keys currently act as a media playback controller through macros.

## BOM:
Here should be everything you need to make this hackpad

- 3x Cherry MX Switches
- 3x DSA Keycaps
- 4x M3x5x4 Heatset inserts
- 4x M3x16mm screws
- 5x SK6812 MINI-E LEDs
- 1x XIAO RP2040
- 1x Case (2 printed parts)