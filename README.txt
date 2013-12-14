An attempt at exporting the SVG assets out of the .fla source files of the Avatar and Avatar Assets.


Avatar.fla has been fully processed.
AvatarAssets.fla is currently in progress. 

Swiffy has trouble with these complex files and throws these errors:
The ActionScript method flash.system.Security.allowDomain() is not supported. (2 occurrences)
The file contains features that may animate too slow as HTML.

Adobe Flash CS6, Flash2Svg (http://www.tbyrne.org/export-flash-to-animated-svg), and Inkscape were used for most of the work.

The Avatar.fla and AvatarAssets.fla folders have the same folder structure as the Avatar.fla file from glitch-avatars
Everywhere that an SVG could be pulled out it was, otherwise there is a .placeholder file there to signify that something was in flash that couldn't be extracted properly.

Some SVGs need more work to be usable, some are animated or should be, not all flash effects are able to directly translate to SVG using current export methods.  Some ActionScript functionality attached to these assets may need to be recreated.

more to come...
