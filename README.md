# opencv_openmv_bridge
This is a minimal code to use openMV camera in openCV on your computer. This code is tested on ubuntu 16.04 but should work on any ubuntu machine with opencv

This Bridge consists of 2 simple codes, one is provided by the openMV team. This code should be on the flash memory of the opennMV board. you can have a look at it from here : https://github.com/openmv/openmv/blob/master/scripts/examples/02-Board-Control/usb_vcp.py
This code is referred as _main.py_ in this project documentation. 

The 2nd code is the opencv based code. Reffered as _opencv_openmv_bridge.py_, it is very small and self explaining itself.

## Setup
1- copy the _main.py_ to your openMV board through either the official IDE. Or simply by copying it to the device.

2- make sure you have opencv for python installed on your device

3- clone this repo: ``` git clone https://github.com/marknabil/opencv_openmv_bridge.git```  

4- navigate to the directory ``` cd opencv_openmv_bridge ```

5- by default the device is assumed to be connected through USB on _ttyACM0_ you can change that in the code part of creating the camera object _device='/dev/ttyACM0'_ , 
You can know what is this number by running ``` dmesg | grep tty ```

## Runing the code
6- ``` python opencv_openmv_bridge.py ``` make sure the file is excutable and enjoy your stream 
