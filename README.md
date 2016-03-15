Sketchup SVG outline plugin
===========================
Fork of [FlightOfIdeas](www.flightofideas.net) Sketchup SVG outline plugin that fixes some bugs that makes it work in the new Sketchup 2015 edition.

The original plugin can be found here: https://code.google.com/p/sketchup-svg-outline-plugin/

The reason I forked this was to fix the use in [Sketchup 2015](http://www.sketchup.com/) and was not able to get in contact with the original author.

Before installation
-------------------
Make sure you have any previous plugin version uninstalled. You might even have to delete the files manually from the Plugins directory (see http://help.sketchup.com/en/article/38583 for details on default location for this).

Installation
------------
1. Download the latest `.rbz` file from [releases](https://github.com/JoakimSoderberg/sketchup-svg-outline-plugin/releases)
2. Go into the Sketchup **preferences**.
3. Under **Extensions**, click **Install extension** and find the `.rbz` file.
4. Make sure the **FlightsOfIdeasSVG** extension is checked in the list of extensions.

Additional information for installing extensions manually: http://help.sketchup.com/en/article/38583

Verify you have the correct version installed
---------------------------------------------
Please note that this version of the plugin only has one button with SVG on it. There should not be any mosquite icon or link to any webpage. If you still see this you have an older version installed still.

If the save button does nothing, this is also an indicator that you have an old version installed. Remove it and reinstall.

Usage
-----

The plugin has its own tool palette. It is made visible through activating the menu item **View > Tool Palettes > FlightsOfIdeas**.
The tool palette has a single button that reads 'SVG':
![Button that reads SVG](/FlightsOfIdeas/Images/CreateSvg.png?raw=true)
To use the plugin, a face in SketchUp needs to be selected. Then, the 'SVG' button can be clicked and the plugin dialogue appears.

