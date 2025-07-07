# ARP-UI
Graphical User Interface for interfacing with ROS2 on RPI 4B

Chromium Kiosk UI built with Flask and Bootstrap to serve onto the touchscreen LCD onboard ARP.

## How to run
Note: ensure that the touchscreen LCD is connected and powered to the RaspberryPi.

1.) Run ```kioskapp.py``` to spin up the Flask app on ```localhost```. 

2.) Run `./openapp.sh` to open up the Chromium instance on ```localhost```.

3.) The interface should appear on the LCD shortly. 
