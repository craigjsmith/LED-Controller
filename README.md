# LED Controller
This program controls RGB LED lights connected to an Arduino from a PC application.

<b>Setup</b>

Connect RGB LED lights to an Arduino. By default, the Arduino is connected on COM3 and lights are connected to the following pins: red on pin 3, green on pin 9, and blue on pin 6. These can be changed in the Java applicaton and the Arduino sketch respectively.

<b>Usage</b>

<img src = "http://i.imgur.com/A3Caz3G.png">

The program features color selectors for primary and secondary colors alongside a color mixer allowing for almost any color. Color brightness can also be controlled. The LEDs will remain on its last setting even after you close the program. The settings will reset if the Arduino looses power or if you relaunch the program.

<b>Credits</b>

SerialClass is modified from <a href = "http://theelectronicist.blogspot.com/2015/02/java-to-arduino-communications-on-linux.html">Jeremy Dunne's Code<a>
