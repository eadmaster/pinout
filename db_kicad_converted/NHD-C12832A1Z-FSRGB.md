128x32 graphical LCD module with common anode RGB backlight, 1/33 duty, 3.3V
lcd rgb st7565r spi 4-wire
https://www.newhavendisplay.com/specs/NHD-C12832A1Z-FSRGB-FBW-3V.pdf


	        +-----------+
	     V0 |[ 1]   [21]| (B)LED-
	     V1 |[ 2]   [20]| (G)LED-
	     V2 |[ 3]   [19]| (R)LED-
	     V3 |[ 4]   [18]| LED+
	     V4 |[ 5]   [17]| ~{CS1B}
	    C2- |[ 6]   [16]| ~{RST}
	    C2+ |[ 7]   [15]| A0
	    C1+ |[ 8]   [14]| SCL
	    C1- |[ 9]   [13]| SDA(SI)
	V_{OUT} |[10]   [12]| V_{DD}
	        +-----------+


generated by https://github.com/FBEZ/Pinout-AsciiArt from https://github.com/ask6483/kicad-symbols/blob/master/Display_Graphic.kicad_sym