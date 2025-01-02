# Notes on this fork

I created this fork of jfedor2's excellent pmw3360-breakout board because I wanted a breakout that would better serve my particular needs.

Specifically, I wanted it to fit the existing plastics of [my trackball design](https://github.com/monroewilliams/trackball), which means having roughly the same dimensions and mounting hole locations as the ones I originally sourced from MrJohnK on Tindie [here](https://www.tindie.com/products/jkicklighter/pmw3360-motion-sensor/) (that one has been discontinued, but there are similar ones available from other sellers on Tindie).

Instead of the 2.54mm pitch pin header, also I wanted it to have a JST-SH (1.0mm pitch) connector with a regularized pinout based on [Pmod type 2](https://en.wikipedia.org/wiki/Pmod_Interface) so I can easily assemble it using compact off-the-shelf cables.

Since I don't need level-shifters (I'm using it with microcontrollers that already have compatible 3.3v logic), this breakout seemed like the perfect starting point. 

Any issues with the changes I made to this layout are solely my fault, so please don't bother jfedor2 with them. :) 

Original (pre-fork) readme follows:

# PMW3360 breakout board

The board doesn't do any level shifting so it only works with 3.3V logic.

The dimensions of the board are 22x34mm and the mounting holes are for M2 screws.

The files in the [fabrication](fabrication) folder can be used to order this board from JLCPCB with SMT assembly. The board you get includes everything except the actual sensor. If some of the specific components are out of stock, try to find an equivalent with the same package and parameters.

The sensor chip should be soldered on the top side (the side where all the other components are). The dot marks pin 1. The optic goes on the bottom side.

![a render of the PCB](PMW3360-breakout-render.png)
