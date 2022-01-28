# DIY Epifluorescence Macroscope and High Power Illuminator
 This is an open-source macroscope design based on the Olympus XLFLUOR 4x/0.28 NA objective.  This macroscope design is fully open-source and is licensed under the Creative Commons Attribution-ShareAlike 4.0 license.  
 
 The development of this scope and illuminator was funded by the following grant: NIH P30EY003176
 
 ![](Images/Macroscope.jpg)
 ## Macroscope and illuminator specs
* FOV: 4.7 mm x 4.7 mm
* Resolution: 1.5 µm 
* Excitation power @ 474/27 nm - 620 mW = 26 mW/mm^2
* Excitation power @ 554/23 nm - 188 mW = 8 mW/mm^2
* Excitation power @ 635/18 nm - 410 mW = 17 mW/mm^2
* LED current: 27 amps
## How to use the CAD files
The CAD files can be opened using FreeCAD: https://www.freecadweb.org/downloads.php  Unless otherwise specified, all the part numbers listed in the CAD file are Thorlabs part numbers.
 ![](Images/LED%20illuminator%20-%20CAD.png)
## Controlling the LEDs
The LEDs can be synced to a camera using a MOSFET and MOSFET driver triggered by the camera.  If using a constant voltage power supply, be sure to include a ballast resistor for stable LED intensity. For programmable control of LED intensity and timing, you can also use the following open-source LED driver: https://github.com/Llamero/Four_Channel_MHz_LED_Driver/tree/High_current
