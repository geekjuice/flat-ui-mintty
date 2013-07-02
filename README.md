flat-mintty
===========

**[Flat-UI](https://github.com/designmodo/Flat-UI) based colorscheme for
mintty/Cygwin.**

*Requirements: [mintty](https://code.google.com/p/mintty/)


How to apply
------------

### In your .minttyrc

* Download [flat-minttyrc](flat-minttyrc) or clone this repository

        git clone git://github.com/geekjuice/flat-ui-mintty

* Then append to existing your .minttyrc:

        cat /path/to/flat-minttyrc >> ~/.minttyrc

* Restart mintty.


### In your .bashrc, .profile, script, etc.

* Download the [flat-mintty](flat-mintty) or clone this repository

        git clone git://github.com/geekjuice/flat-ui-mintty

* Then either source the script or load it from bashrc, profile, etc.

        source /path/to/flat-mintty


How to tweak
------------

If the color settings provided are not quite what you want, feel free to
mix-and-match whatever colors you can think of.

* Download the appropriate colorscheme based on how to you wish you install it

* To change a color, find the [ANSI
  Color](http://en.wikipedia.org/wiki/ANSI_escape_code) you wish to overwrite
  and replace it with the corresponding RGB color (e.g. 255,0,0 for red) or HEX
  Triplet (e.g. #FF0000) for flat-minttyrc and flat-mintty respectively.

* Install using the instructions above, but point the source file to your custom
  coloescheme


Troubleshoot
------------

Q: The colors don't seem to be applied or rendering correctly even after
restarting mintty...

A: There's a good change your terminal isn't set to proper color setting. In
mintty, go to Options > Terminal > Type and select xterm-256color
It is also a good idea to set it within the terminal by adding the
following line to wither your bashrc, profile, etc.

        export TERM=xterm-256color


Q: I applied the colors using flat-mintty, but decided to go back to the
default colors.

A: I haven't tested this, but in case deleting the script and restarting
mintty doesn't revert back to the default colorscheme, you download the 
[default-mintty](default-mintty) script provided to revert back to normal.


License
-------
flat-ui-mintty is released under the [MIT
License](http://www.opensource.org/licenses/MIT)
