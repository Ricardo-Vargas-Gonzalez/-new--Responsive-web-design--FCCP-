# on this project I´m create different types of colors

from primary colors
There are three more tertiary colors: chartreuse green (green + yellow), azure (blue + cyan), and rose (red + magenta).

To create chartreuse green, update the rgb function in the .one rule so that red is at 127, and set green to the max value.

For azure, update the rgb function in the .two rule so that green is at 127 and blue is at the max value.

And for rose, which is sometimes called bright pink, update the rgb function in the .three rule so that blue is at 127 and red is at the max value.

## hexagonal color model

### HSL color model

The HSL color model, or hue, saturation, and lightness, is another way to represent colors.

The CSS hsl function accepts 3 values: a number from 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness.

If you imagine a color wheel, the hue red is at 0 degrees, green is at 120 degrees, and blue is at 240 degrees.

Saturation is the intensity of a color from 0%, or gray, to 100% for pure color.

Lightness is how bright a color appears, from 0%, or complete black, to 100%, complete white, with 50% being neutral.

#### gradient

A gradient is when one color transitions into another. The CSS linear-gradient function lets you control the direction of the transition along a line, and which colors are used.

One thing to remember is that the linear-gradient function actually creates an image element, and is usually paired with the background property which can accept an image as a value.
