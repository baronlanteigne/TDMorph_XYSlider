# TDMorph_XYSlider

This is a simple XY slider GUI .tox for TouchDesigner. It requires the [TDMorph](https://github.com/DarienBrito/TDMorph) .tox created by [DarienBrito](https://github.com/DarienBrito). Each corner of the 2D slider is associated with a stored preset in TDMorph. The resulting output is mapped to TDMorph for a seamless integration letting you store new presets created with this module. This project was inspired by a suggestion by [aaapoc](https://github.com/aaapoc).

## Requirements:
* [Touchdesigner](https://derivative.ca/)
* [TDMorph](https://github.com/DarienBrito/TDMorph)

## Limitations:
Current design of this slider will override your current OSC mapping with TDMorph. Hopefully this limitation can be improved on in the future.

## Step by Step setup:
* Import TDMorph_XYSlider.tox in your project.
* Associate XYSlider to TDMorph by changing the first parameter, labeled TDMorph COMP, to the path of your TDMorph node.
* Set the four presets you want to use with the slider. By default, XYSlider will select the first 4 presets stored in TDMorph.
* Click the update pulse button to load these values.
* At the moment, the update button needs to be clicked whenever you update any of the 4 presets you selected or whenever you want to select different presets.
* [Check out the provided example](/examples) .toe file for a quick demo.

Johann Baron Lanteigne
https://baronlanteigne.com/