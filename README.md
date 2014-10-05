
**svg-prism** is a tool to export Android drawables at different sizes, from a single SVG source.

The Android Studio directory layout is assumed. The tool must be run from $projectdir/app/src/main, and the source svg's are expected to reside in the 'drawable-src' subdirectory.

svg-prism uses Inkscape for the actual export, so that needs to be installed.
Sizing is based on the SVG document size.


## Usage ##
svg-prism [command]

**Commands are:**

drawable (default)
Generates all images except the launcher icon

icon
Generates launcher icons from 'ic_launcher.svg'
