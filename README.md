# iOS 11 GUI for Framer

<br>

![][image-1]

<br>

An iOS 11 graphical user interface kit assembled in Framer by [@brentcas][1].

To open the Framer files, you need to have [Framer][2] installed on your macOS device. Download one of Apple’s [iOS UI Design Resources][3] for access to the San Fransisco Pro font. This collection of files is organized into folders like so:

> 01-Style
> - 01-Colors.framer
> - 02-Fonts.framer

> 02-iPhone-8-Elements
> - 01-System.framer
> - 02-Bars.framer
> - 03-Controls.framer
> - 04-Views.framer
> - 05-Keyboards.framer

> 03-iPhone-X-Elements
> - 01-System.framer
> - 02-Bars.framer
> - 03-Controls.framer
> - 04-Views.framer
> - 05-Keyboards.framer
> - 06-Safe-Areas.framer

Each Framer file has a collection of designed elements, and contains no prototype code for interactive behavior. These assets are for the purposes of copying and pasting into your own prototypes, or being used as a design reference.

## Style Guide

### Naming

Each UI layer should be given a code compatible name using camelCase following Google’s JavaScript [style guide][4].  Names should typically be structured as `element`, `state`, `color`. So, the light version of the status bar with a back button would be `statusBarBackLight`.

If a shape is the only layer within a frame, that frame can have the same name as the shape. Paths, groups, and joins within shapes do not need to be named.

### Positioning Shapes

Shapes should always be within a fixed frame that is responsively positioned. If a shape is part of a group of other layers within a fixed frame, it doesn’t need an additional frame.

## Footnotes

Brent Caswell can be contacted on Twitter [@brentcas][5] or via email at [caswell.brent@gmail.com][6].

This project includes photography by [Quentin Keller][7], [Toa Heftiba][8], [Caleb George][9], and [Eduardo Dutra][10] under the [Unsplash license][11].

All files have been opened on Framer v112 and may have issues on other versions of Framer. This project is not affiliated with Apple, Framer, or Domino’s Pizza. Please see the license for more legal gobbledegook.

[1]:	https://github.com/brentcas
[2]:	https://framer.com/
[3]:	https://developer.apple.com/design/resources/
[4]:	https://google.github.io/styleguide/jsguide.html#naming-camel-case-defined
[5]:	https://twitter.com/brentcas "@brentcas"
[6]:	mailto:caswell.brent@gmail.com "caswell.brent@gmail.com"
[7]:	https://unsplash.com/@kt1klr
[8]:	https://unsplash.com/@heftiba
[9]:	https://unsplash.com/@seemoris
[10]:	https://unsplash.com/@edwardutra
[11]:	https://unsplash.com/license

[image-1]:	https://raw.githubusercontent.com/brentcas/iOS-11-Framer/master/README-Images/shots@2x.png