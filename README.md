# H-Link-Docs
## Software

https://github.com/lumixen/esphome-hlink-ac

## Hardware

### Heatpump

Model Number: 

RAS-70YHA2

### Components
Connector used (JST PH2.0):

(does not fit without modification, I do not reccomend using, if purchasing use HY2.0):

https://www.aliexpress.com/item/1005007389108799.html

Logic level converter:

https://www.aliexpress.com/item/1005005984772131.html

Buck converter:

https://www.aliexpress.com/item/1005007031557776.html

ESP32 (CP2102):

https://www.aliexpress.com/item/1005006617407766.html

## Instructions:
### Step 1: Heat Pump Dissasembly:
 - turn of heatpump at master switch

Switch is typically located near the outdoor unit, ensure the green light is no longer illuminated on the indoor unit.

 - Remove three screws

These are located along the bottom side of the indoor unit with  plastic covers that just pull off.

 - Undo 6 clips

Using a flat srewdriver first undo to 4 along the top followed by the two under the filter cover.

 - Remove the electronics housing cover

Remove Tape if present and undo three screws

### Modifying Connector:
If you have a PH2.0 you will need to file down both sides.

### Determin socket Orientation:
Using a multimeter find the wire that gives ~12V and ground (For me it was the following layout with 12V at the bottom).

![image](https://github.com/user-attachments/assets/774b9f2d-0b40-4f59-9ab1-4998cb9af368)

### Wiring
Follow the original diagram including using pin 16 and 17 for UART

![image](https://github.com/user-attachments/assets/f5737485-2d1a-44ac-94b3-189e04d45427)
![image](https://github.com/user-attachments/assets/4ce03b9a-939a-4480-a8fd-891162213673)


