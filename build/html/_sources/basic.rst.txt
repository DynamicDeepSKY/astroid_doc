.. _basic:

Web Interface
========================

Status Icons
--------------


App Icons
--------------



Camera Control
--------------




2D Mode 
------------------



3D Mode 
------------------



Setting Up License
-----------------------

1. Once you receve the license key by email copy the key and paste it in the setting menu and press set license button.
2. Refresh the screen with F5 key and check the system info menu to see if your license is recognized correctly 



Hot Pixel Correction
--------------------

Over time the number of hot pixel increses. These hot pixels are especially noticeable if you run EAA stacker with tracking option on. Astroid has a built-in hot pixel dector and corrector. But to correct the hot pixel you need to manually activate the hot pixel dector. Please follow the following procedure to detect the hot pixels. 

1. Complete block the lens port of Astroid. Turn off every light around the room and make it completely dar. The DDS made lens cover will be available soon.
2. To go camera setting and increase exposure to maximum and set gain to 150.
3. Go to system menu and adjust hot pixel level. Lower value will pick more hot pixels. Try with the default value and if you still see some week hot pixels, lower the value little bit more until satisfactory.
4. Click hot pixel correction button.
5. Run EAA stacker and see if hot pixels are disappeared




Image Download
--------------



Changing WIFI SSID and Pass
---------------------------

The default Wifi SSID is DDS_DIRECT but you can change it what ever you want. Just go to the system setup and type SSID and Pass you want and press set button.




.. admonition:: Warnning

    If you cut the power without parking Astroid, sometime SD card is currped and you have to recover it to factory setup.


Writing Images to USB Memory
------------------------------

1. Format a usb memory with NTFS format
2. Change name to DDS
3. Insert the usb to Astroid and see if USB buttons are recognized
4. Click the save button



.. admonition:: Warnning

    Use high speed USB memorys only. With low speed usb, Astroid will continue to write files to USB even after you finished recording which will drastically increases the chance of file curruption.

.. admonition:: How to eject

    USB must be ejected after eject button is clicked and all the usb related icons are disappeared. Otherwise, the USB will be currupted and you will lost all data in the USB.
    

Making DDS USB
------------------------------


Changing Web Address
--------------------

If you have to run multiple Astroid camera under a same network you should change it's host ID. Log in to Astroid using SSH and change host name in raspi-config.

