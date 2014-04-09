 Changelog
------------------------

------------------------
-- Version 1.57
------------------------
-- * Some bugfixes and compatibility for EvoRTS
-- * Bug fixes and performance improvements
-- * Added TS values and better handling of screen position
-- * Improved player list management and handling of dead players
-- * Fixed bug where team bars disappear even if team is alive


------------------------
-- Version 1.5
------------------------
-- * Rewritten code to increase performance, fps cost down by 50% in normal usage scenario.
-- * Now uses drawlists and gl.loadFont


------------------------
 Version 1.41
------------------------

 * Bug fixes and performance improvements


------------------------
 Version 1.4
------------------------
 * Performance improvements
 * Font improvements
 * Display extended info by pressing on i-button instead of overcomplicated arrows
 * Drag widget with right button; drag infopanel with left button and close with right (yes i know, maybe counter-intuitive)
 * Fixed opengl bugs


------------------------
 version 1.32
------------------------
 * Compatible with spring 95.0
 * fixed bug with incorrect expand button location
 * fixed spam errors bc of old tags


------------------------
 Version 1.3
------------------------
  * Added possibility to move the statistics table. To move it, click on the move button at top left and drag the window where you want it.
  * Added option tomove to next and previous team from within the statistics table. Use the arrows beside team number to do that.
  * Fixed some bugs that appear when widget is on the left side of the screen.
  * The statistics window is now closed by right-clicking on it (or pressing the close/collapse button on the widget).


------------------------
 Version 1.2
------------------------
  * Ctrl+click on arm/core image to zoom in on player's commander (if alive)
  * Fixed sorting of kill distribution graph
  * Fixed some bugs relating to more start positions than players in game
  * Fixed speeded up blink rate when increasing game speed.


------------------------
 Version 1.11
------------------------
 Fixed load/save bug
 Player kill distribution graph added.


------------------------
 Version  1.1
------------------------
 * Added many options to tweak screen, press ctrl+F11 to customise widget
 * Saves settings now
 * Click on arm/core image to go to player start position
 * Changed kills/losses bar to display killed hp/lost hp instead of kills/losses
 * Added active player mode, can be disabled/customised in options
 * Made calls more efficient by moving stuff out of drawscreen function




		name = "Ecostats",
		desc = "Display team eco",
		author = "Jools",
		date = "jan, 2014",
		license = "GNU GPL, v2 or later",
		layer = 99,
		enabled = false


------------------------
Installation:
------------------------

* Unzip widget to <Springdir>/LuaUI/Widgets
* Unzip sounds to <Springdir>/LuaUI/Sounds
* Unzip fonts to <Springdir>/LuaUI/Fonts
* Unzip images to <Springdir>/LuaUI/Images/ecostats

------------------------
------------------------
Feedback welcome to springjools at gmail.com

Jools