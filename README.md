# opencv_openmv_bridge
This is a minimal code to use openMV camera in openCV on your computer


This Bridge consists of 2 simple codes, one is provided by the openMV team. This code should be on the flash memory of the opennMV board. you can have a look at it from here : https://github.com/openmv/openmv/blob/master/scripts/examples/02-Board-Control/usb_vcp.py

The 2nd code is the opencv based code. It is very small and self explaining itself.

## Setup
1- copy the _main.py_ to your openMV board through either the official IDE. Or simply by copying it to the device.

2- make sure you have opencv for python installed on your device

3- clone this repo: ``` git clone https://github.com/marknabil/opencv_openmv_bridge.git```  

4- navigate to the directory ``` cd opencv_openmv_bridge ```

5- ``` python opencv_openmv_bridge.py ``` and enjoy your stream 
