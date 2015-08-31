Galileo Board SD card Linux

version iot 1.1.0 dirty + Kernel 3.19.2 (custom build xbolshe)

Original source code:
- https://downloadcenter.intel.com/download/23197/Intel-Quark-BSP
- https://github.com/robopeak/rpusbdisp
- http://git.open-mesh.org/

See source code for license information.

Notes:
- this is a development version. Not all drivers and features may work correctly;
- it was mostly tested on Galileo Gen2 board;
- some problems with SPI driver (and as result with analog inputs A0-A5 of the board);


01 Sep 2015
 - change uart8250 to quark_uart driver for ttyS0/ttyS1
 - add B.A.T.M.A.N. (see http://www.open-mesh.org/projects/open-mesh/wiki)  (!! not tested !!)
   Use the following commands:
       - modprobe batman-adv
       - batctl
       - alfred


29 Aug 2015
 - Add Robopeak USB display driver (https://github.com/robopeak/rpusbdisp)

  ![alt robopeak](robopeak.jpg?raw=true "robopeak")

  ![alt robopeak2](robopeak2.jpg?raw=true "robopeak2")

24 Aug 2015
 - create spidev1.0 from spidev169.0 (dynamic spidev)

23 Aug 2015
 - some fixes in Gen1 drivers

22 Aug 2015
 - first release


xbolshe

