# Foreground Color
# color
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:
rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)
hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80
color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan
We look at these three different
ways of specifying colors on the
next double-page spread.
CSS3 has also introduced
another way to specify colors
called HSLA, which you will
meet near the end of this chapter
on page 255-256.
Foreground Color
color
Above each CSS rule in this
example you can see how CSS
allows you to add comments
to your CSS files. Anything
between the /* symbols and
the */ symbols will not be
interpreted by the browser.
They are shown in grey above.
The use of comments can help
you to understand a CSS file
(and organise it, by splitting a
long document into sections).
Here, we have used comments
to indicate which method is used
to specify each of the different
types of colors



# Background Color
# background-color

CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.
You can specify your choice of
background color in the same
three ways you can specify
foreground colors: RGB values,
hex codes, and color names
(covered on the next page).
If you do not specify a
background color, then the
background is transparent.
By default, most browser
windows have a white
background, but browser users
can set a background color for
their windows, so if you want
to be sure that the background
is white you can use the
background-color property on
the <body> element.
We have also used the padding
property to separate the text
from the edges of the boxes.
This makes it easier to read and
you will learn more about this
property on page 313.


Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.
Understanding Color
Computer monitors are made
up of thousands of tiny squares
called pixels (if you look very
closely at your monitor you
should be able to see them).
When the screen is not turned
on, it's black because it's not
emitting any light. When it's
on, each pixel can be a different
color, creating a picture.
The color of every pixel on the
screen is expressed in terms of
a mix of red, green, and blue —
just like on a television screen.
Color picking tools are available
in image editing programs like
Photoshop and GIMP. You can
see the RGB values specified
next to the radio buttons that
say R, G, B.
The hex value is provided
next to the pound or hash
# symbol. There is also a
good color picking tool at:
colorschemedesigner.com

Hue
Hue is near to the colloquial idea
of color. Technically speaking
however, a color can also have
saturation and brightness as
well as hue.
Saturation
Saturation refers to the amount
of gray in a color. At maximum
saturation, there would be no
gray in the color. At minimum
saturation, the color would be
mostly gray.
Brigh tness
Brightness (or "value") refers
to how much black is in a color.
At maximum brightness, there
would be no black in the color.
At minimum brightness, the
color would be very dark.
CSS3 introduces the opacity
property which allows you to
specify the opacity of an element
and any of its child elements.
The value is a number between
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15%
opacity).
The CSS3 rgba property allows
you to specify a color, just like
you would with an RGB value,
but adds a fourth value to
indicate opacity. This value is
known as an alpha value and is
a number between 0.0 and 1.0
(so a value of 0.5 is 50% opacity
and 0.15 is 15% opacity). The
rgba value will only affect the
element on which it is applied
(not child elements).
Because some browsers will
not recognize RGBA colors, you
can offer a fallback so that they
display a solid color. If there are
two rules that apply to the same
element, the latter of the two
will take priority. To create the
fallback, you can specify a color
as a hex code, color name or
RGB value, followed by the rule
that specifies an RGBA value. If
the browser understands RGBA
colors it will use that rule. If it
doesn't, it will use the RGB value.
At the time of writing, the
opacity and rgba properties
are only supported by the most
recent browsers.