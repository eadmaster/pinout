Dual UART with I2C/SPI interface, 64 bytes of transmit and receive FIFOs, IrDA SIR built-in support, HVQFN-32
UART I2C/SPI 64B FIFO IrDA SIR
https://www.nxp.com/docs/en/data-sheet/SC16IS752_SC16IS762.pdf


	           +-----------+
	       RXA |[ 1]   [33]| VSS
	  ~{RESET} |[ 2]   [32]| TXA
	     XTAL1 |[ 3]   [31]| ~{CTSA}
	     XTAL2 |[ 4]   [30]| ~{RTSA}
	       VDD |[ 5]   [29]| VSS
	I2C/~{SPI} |[ 6]   [28]| VDD
	  A0/~{CS} |[ 7]   [27]| GPIO7/~{RIA}
	     A1/SI |[ 8]   [26]| GPIO6/~{CDA}
	   N.C./SO |[ 9]   [25]| GPIO5/~{DTRA}
	  SCL/SCLK |[10]   [24]| GPIO4/~{DSRA}
	   SDA/VSS |[11]   [23]| RXB
	       VSS |[12]   [22]| TXB
	       VDD |[13]   [21]| VSS
	    ~{IRQ} |[14]   [20]| GPIO3/~{RIB}
	   ~{CTSB} |[15]   [19]| GPIO2/~{CDB}
	   ~{RTSB} |[16]   [18]| GPIO1/~{DTRB}
	           +-----------+


generated by https://github.com/FBEZ/Pinout-AsciiArt from https://github.com/ask6483/kicad-symbols/blob/master/Interface_UART.kicad_sym