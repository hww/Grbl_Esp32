

# CoilWinder based on grbl for ESP32

The coil winder based on [Grbl_ESP32](https://github.com/bdring/Grbl_Esp32). 

Added:

- _coilwinder_ machine with settings for two step motors with 6600 drivers. 

- Modifyed _Report.cpp_ contains a bit clucky SSD1306 code for displaying CNC status (see image below).

<img src="https://github.com/hww/coil_winder_grbl_esp32/blob/main/doc/oled_display.jpg" width="300">

The _coilgen_ folder cotains a python script for generating gcode from a coil's params. The file have the a wire turn and layer number as a comment. The comment will be displayed on OLED display. 

In general i do not like _grbl_ but it saved my time and i can make my coils quicker now. 


