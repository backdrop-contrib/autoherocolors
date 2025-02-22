# Automatic Hero Colors

Automatically sets the text color of hero blocks based on the average color
of the background image, to fix contrast problems. Sets the background color to
the average image color.

Does nothing if no image is set in that hero block.

**A problem:** you upload an image to use as hero background, but it's rather
light (or dark), but the theme has a fixed color for all hero blocks. You
might end up with unreadable text (not enough contrast between background
and foreground).

You can update the theme, or use the CSS Injector module to fix that. But
then you change the image, and you have to update that CSS again.
Or you have multiple hero blocks, either in the same layout or different
ones, and some background images are light, others are dark...

**Another problem:** If a background image loads rather slow (on slow
connections), there's this flash before the image is loaded, especially with
dark images, and the text on top might be hard to recognize.

**Solution:** Install this module and stop worrying about that.

## Installation

Install this module using the official 
  [Backdrop CMS instructions](https://docs.backdropcms.org/documentation/extend-with-modules)

## Dependencies

No hard requirement, but this module is only useful, if the Image module
(core) is enabled.

Color calculation is done using GD.

## Issues

Bugs and Feature requests should be reported in the 
 [Issue Queue](https://github.com/backdrop-contrib/autoherocolors/issues)

## Current Maintainers

- [Indigoxela](https://github.com/indigoxela)

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
