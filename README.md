# ESP8266 Deauther Version 2

<p align="center">
  <img alt="PICTURE logo" src="https://raw.githubusercontent.com/wiki/spacehuhn/esp8266_deauther/img/deauther_logo.png" width="200">
  <br>
  <b>Scan for WiFi devices, block selected connections, create dozens of networks and confuse WiFi scanners!</b>
  <br>
  <br>
</p>

Install using .bin file

-  Download latest compiled .bin file from nightly-deauther/releases
<br>
-  Install esptool
<br>
-  Connect your ESP8266
<br>
-  Flash it by running esptool.py -p <PORT> -b 115200 write_flash 0 <BIN_FILE>.
<br>
-  Be sure to replace <PORT> with the serial port
and <BIN_FILE> with the path of the previously download .bin file.
