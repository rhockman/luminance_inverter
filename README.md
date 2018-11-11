# Luminance Inverter

Bright screens when you're trying to sleep are no fun.  I really like the program [f.lux](https://justgetflux.com/) for reducing the amount of blue light that comes from the display, but reading a white-background webpage at night can still be unpleasant.

You could always do a straight inversion, but then the colors aren't right.  I got to thinking about colorspaces and wondered what things would look like if you kept the same hue and saturation, but inverted the brightness or luminance.  You'd maintain a similar theme and contrast, but it would tone things down a bit if they were too bright.  (And, conversely, if they were too dark, make them real bright)

This little workbook is me figuring out what that actually looks like.

Put any images you want converted in the `images` directory.  This will find them, invert the luminance, and drop the result in the `inverted` directory.

**Warning** This thing is slow.  Several seconds per image.

Images are expected to be color images in sRGB.

Developed on Python 3 with Anaconda, but so long as you have skimage and juptyer you should be ok.  LMK if I'm wrong.

