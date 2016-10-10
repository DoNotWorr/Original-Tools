Changelog

v1.57
TibiaCam
Fixed .cam files not showing up in browser
Fixed .cam files not being detected as playable format when launching from file manager


v1.56
Experience Counter
Fixed using Level% causing the program to crash if you did not gain >=1%
TibiaCam
Added support for .cam files (created by the new custom client)


v1.55
TibiaCam
Added support for 7.72


v1.54
TibiaCam
Fixed a bug that would cause the client to crash if a packet bigger than 8192 bytes was received


v1.53
TibiaCam
Fixed a bug that prevented playback hotkeys from working
Added text commands
Hotkeys
Added gold counter
Made it easier to create new hotkeys
General
Fixed not loading some settings properly


v1.52
TibiaCam
Fixed a bug that would cause only the test login server IP to be overwritten
Fixed a bug that prevented rewinding in playing recordings the non-traditional way
Experience Counter
Added things that was supposed to be in 1.5


v1.51
Fixed the program crashing upon startup for some users


v1.5
TibiaCam
Added MoTD
Added playback options
Added recording of mouse movements
Duration is now shown correctly on certain recordings
Now automatically associates .kcam files with Tibianic Tools
Experience Counter
Added option to count time TNL based on gained level percent or the experience TNL formula
Added option to estimate experience TNL based on gained experience and gained level percent
Changed experience table to Tibianic's experience table (only up to level 110)
UI
Replaced the images for closing, minimizing and hiding to tray
Added context menu (right-click on tray icon)
Fixed client chooser only showing max 2 clients on first dropdown


v1.44
Source
Some more code cleanup (sigh...)
TibiaCam
Fixed a critical error introduced in 1.43 that didn't save metadata in new recordings,
which made them unplayable

v1.43
Source Added Packet class (..\Objects\Packet.cs)
Added Network class and ThreadSafe class (..\Utils.cs)
Cross-threading errors should now be gone while debugging
More code cleanup
General
Disabled visual styles (i.e. Vista and W7 had big ugly white borders on buttons)
TibiaCam
Fixed compability with tibianic.org (DNS only)

v1.42
General
Minor code cleanup
Slightly improved memory reading
Will now automatically position itself in the top left window of Tibia when run
Now open source
HUD
Added FPS counter for 7.6
TibiaCam
Slightly improved playback performance (only users with low-end CPUs will notice any difference)
Made the automatic playback better