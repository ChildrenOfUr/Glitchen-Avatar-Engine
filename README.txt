An attempt at exporting the SVG assets out of the .fla source files of the Avatar and Avatar Assets.

Currently only Avatar.fla has been processed.  

This needs to be done manually as Swiffy has trouble with these complex files and throws these errors:
The ActionScript method flash.system.Security.allowDomain() is not supported. (2 occurrences)
The file contains features that may animate too slow as HTML.

Adobe Flash CS6, Flash2Svg (http://www.tbyrne.org/export-flash-to-animated-svg), and Inkscape were used for most of the work.

The Avatar.fla folder has the same folder structure as the Avatar.fla file from glitch-avatars
Everywhere that an SVG could be pulled out it was, otherwise there is a .placeholder file there to signify that something was there that couldn't be extracted properly.

Of the SVGs that are there, some don't seem to properly represent the transparency and/or texture and lighting effects of the original file.  Most also need some sort of background replacement and/or canvas resizing.

more to come...