Galileo Board SD card Linux

version iot 1.1.0 dirty + Kernel 3.19.2 (custom build xbolshe)

USE LINK TO DOWNLOAD:
https://www.relvarsoft.com/galileo/galileo_iot_1.1.0_dirty_custom_build_xbolshe_kernel_v3.19.2_201510041.zip


Original source code:
- https://downloadcenter.intel.com/download/23197/Intel-Quark-BSP
- https://github.com/robopeak/rpusbdisp
- http://git.open-mesh.org/
- https://github.com/intel-iot-devkit/mraa
- https://w1.fi/hostapd/
- https://launchpad.net/ubuntu/+source/iw
- https://wireless.wiki.kernel.org/en/developers/regulatory/crda


See source code for license information.

Notes:
- this is a development version. Not all drivers and features may work correctly;
- it was mostly tested on Galileo Gen2 board;
- some problems with SPI driver (and as result with analog inputs A0-A5 of the board);


04 Oct 2015
 - update nodejs to 4.1.1, mraa 0.8.0, upm 0.4.0

  ![alt jssql](jssql.jpg?raw=true "jssql")


27 Sep 2015
 - update nodejs to 4.1.0
 - add nginx 1.9.5 with http/2

  ![alt njs41_2](njs41_2.jpg?raw=true "njs41_2")


  ![alt wsngx](wsngx2.jpg?raw=true "wsngx")


13 Sep 2015
 - add tcpdump v4.7.4, upm v0.3.2

08 Sep 2015
 - add for WiFi: hostapd v2.4, iw v4.1, crda

   - Use <b>iw reg set your_country_code_2_charcaters</b> to enable WiFi frequencies more than 1-11 channels
   - Use hostapd /etc/hostapd.conf to enable AP

 - add mraa v0.7.4
   - Examples are located in /examples/mraa/

03 Sep 2015
 - add nodejs v0.12.7, perl v5.14.3, sqlite3 v3.8.3.1, mailx v12.5

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

