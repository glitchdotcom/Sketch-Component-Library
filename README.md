# Sketch-Component-Library [Experimental]
Component Library for Glitch Community 

## Overview
This repo contains the following items:
* The Glitch Component Library is a Sketch Library that contains basic UI components from the Glitch Community site. 
* Data that enables you to grab common assets (like project avatars and names) to use in your Sketch files.
* The glitch-community sketchpalette, used to load current color set from `global.styl` into Sketch with the [sketch-palettes](https://github.com/andrewfiorillo/sketch-palettes) plugin

## Instructions
### For the Component Library:
1. Clone this repo.
2. In Sketch, add the component-library file as a library under Preferences > Libary > Add Library
3. Now in any new Sketch file, when you add a symbol, you can add a symbol from the Component-Library. Most components are nested symbols, so you should be able to edit the contents on the fly without affecting the style.

**Note:**
Nested dynamic buttons are not supported in Glitch, so for certain items like pop-overs, you should copy the item directly from the `component-library` sketch file rather than inserting it as a symbol.  Using the [Paddy Sketch library](https://github.com/DWilliames/paddy-sketch-plugin), the buttons should resize when you change its label.

### To load data:
1. Go to Preferences > Data and click the `Add Data...` button
2. Select all the files in the `data` folder.
3. Now when you use items from the component library, you can use `cmd+d` to cycle data automatically, or you can right click on any image or text to replace it with a data object.

### To load the sketchpalette
1. Install the [sketch-palettes plugin](https://github.com/andrewfiorillo/sketch-palettes)
2. Go to Plugins > Sketch Palettes > Load Palette... and select the `glitch-colors.sketchpalette` file
3. Load as a global preset to have the palette accessible in all your documents.

## Library Components
### Viewports
Artboards for all of the breakpoints on the Community site

### Components
* Buttons
* Cards (Project / Feature/ Collection - profile & homepage)
* Info (User / Team / Project)
* Pop-overs
* Avatars (Users / Teams / Projects / Features)

### Appearances
* Button background colors
* Card colors (private / public)
* Popover containers (action / info)
