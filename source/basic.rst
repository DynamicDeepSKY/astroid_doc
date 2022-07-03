.. _basic:

Web Interface
========================

User Interface Layout
------------------------

.. figure:: /images/screen_component.png
   :width: 700
   :alt: Finder align 
   :align: center

1. Camera image
2. Quick control icon bar
3. Status icons
4. ARZoom image
5. Quick menu
6. Search
7. Search result

Status Icons
--------------

|bolt_green| Power normal

|bolt_red| Unstable power

|eye_green| Sky recognized

|eye_red| Sky recognition failed

|eject_red| Don't eject USB

|update| System update in progress

|satellite_green| GPS valid

|satellite_red| GPS input required

|save_green| Inave save on

|temp_green| CPU temparature is in normal range 

|temp_red| CPU is overheated

|usbmemory_green| USB recognized


.. |bolt_green| image:: /images/bolt_green.png
                :scale: 50 %
.. |bolt_red| image:: /images/bolt_red.png
                :scale: 50 %

.. |eye_green| image:: /images/eye_green.png
                :scale: 50 %
.. |eye_red| image:: /images/eye_red.png
                :scale: 50 %


.. |eject_red| image:: /images/eject_red.png
                :scale: 50 %
.. |update| image:: /images/update.png
                :scale: 50 %


.. |satellite_green| image:: /images/satellite_green.png
                :scale: 50 %
.. |satellite_red| image:: /images/satellite_red.png
                :scale: 50 %


.. |save_green| image:: /images/save_green.png
                :scale: 50 %
.. |save_red| image:: /images/save_red.png
                :scale: 50 %


.. |temp_green| image:: /images/temp_green.png
                :scale: 50 %
.. |temp_red| image:: /images/temp_red.png
                :scale: 50 %


.. |usbmemory_green| image:: /images/usbmemory_green.png
                :scale: 50 %
.. |usbmemory_red| image:: /images/usbmemory_red.png
                :scale: 50 %





Quick control icons
-------------------------


|setting| Advanced setting menu open/close

.. |setting| image:: /images/setting.png
                :scale: 60 %
                
|liveps| Live sky recognition on/off

.. |liveps| image:: /images/liveps.png
                :scale: 60 %

|stack| Staker on/off

.. |stack| image:: /images/stack.png
                :scale: 60 %

|search| Star search

.. |search| image:: /images/search.png
                :scale: 60 %

|starlist| Open/close star list 

.. |starlist| image:: /images/starlist.png
                :scale: 60 %

|dgs_align| Camera align mode on/off to the main telescope 

.. |dgs_align| image:: /images/dgs_align.png
                :scale: 60 %
                
|AR| Augmented reality mode on/off       
                
.. |AR| image:: /images/AR.png
                :scale: 15 %
                
|showstar| Star display on/off                     
                
.. |showstar| image:: /images/showstar.png
                :scale: 60 %
                
|showdso| DSO display on/off                   
                
.. |showdso| image:: /images/showdso.png
                :scale: 60 %
                
|autodso_search| Nearist DSO auto display on/off        
                
.. |autodso_search| image:: /images/autodso_search.png
                :scale: 60 %
                
|const| Constellation display on/off        
                       
.. |const| image:: /images/const.png
                :scale: 60 %
                
|timelapse| Time lapse start/end       
                
.. |timelapse| image:: /images/timelapse.png
                :scale: 60 %
                
|nightmode| Night mode on/off  
                
.. |nightmode| image:: /images/nightmode.png
                :scale: 60 %
                
|eclgrid| Elliptical grid on/off  

.. |eclgrid| image:: /images/eclgrid.png
                :scale: 60 %
                
|azigrid| Azimuth grid on/off  
                
.. |azigrid| image:: /images/azigrid.png
                :scale: 60 %
                
|fullscreen| Full screen mode (Android and Desktop only)
                
.. |fullscreen| image:: /images/fullscreen.png
                :scale: 60 %
                
|polaralign| Polar align mode start
             
.. |polaralign| image:: /images/polaralign.png
                :scale: 60 %
                
|imgdown| Image download
                
.. |imgdown| image:: /images/imgdown.png
                :scale: 60 %
                
|imgdown| Eject USB memory
                
.. |ejectmain| image:: /images/ejectmain.png
                :scale: 60 %
                
|refresh| Refresh screen
                
.. |refresh| image:: /images/refresh.png
                :scale: 60 %
                
|refresh| Power off
                
.. |power| image:: /images/power.png
                :scale: 60 %



Camera Control
--------------


.. figure:: /images/camera_ctrl.png
   :alt: Finder align 
   :align: center

Exposure: Sensor exposure time in second.

Gain: Sensor gain 

ImageQuality: JPG image quality in percentage. Higher value increase file size and image quality but slower the frame transfer rate.

FlipImage: This option will flip image which might be useful in some mounting conditions.

ZoomMode: Turning this optin will force Astroid to send down sized image in faster frame transfere rate. This option is usuful when focusing.


ZoomSize: Image size in pixel.





Setting Up License
-----------------------

.. admonition:: Information

    You need to activate a license key only in two cases: 1. when you ordered a new app license code. 2. when you ordered a diy kit

1. Once you receve the license key by email copy the key and paste it in the setting menu and press set license button.
2. Refresh the screen with F5 key and check the system info menu to see if your license is recognized correctly 

.. figure:: /images/systeminfo.png
   :width: 400
   :alt: Version check
   :align: center

.. figure:: /images/license_check.png
   :width: 400
   :alt: Finder align 
   :align: center


Hot Pixel Correction
--------------------

The number of hot pixel naturally increses over time. These hot pixels are especially noticeable if you run EAA stacker with tracking option on. Astroid has a built-in hot pixel dector and corrector. But to correct the hot pixel you need to manually activate the hot pixel dector. Please follow the following procedure to detect the hot pixels. 

1. Complete block the lens port of Astroid. Turn off every light around the room and make it completely dar. The DDS made lens cover will be available soon.
2. To go camera setting and increase exposure to maximum and set gain to 150.
3. Go to system menu and adjust hot pixel level. Lower value will pick more hot pixels. Try with the default value and if you still see some week hot pixels, lower the value little bit more until satisfactory.
4. Click hot pixel correction button.
5. Run EAA stacker and see if hot pixels are disappeared



Changing WIFI SSID and Pass
---------------------------

* Using this option is currently not recommanded due to a bug. Don't use this option until there is further notice.
 
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

1. Prepare a SanDisk 32GB Ultra Fit or equivalant. High speed USB memory is highly recommanded to prevent any data lost
2. Format the disk with NTFS format and change name to DDS. 
3. Insert the USB to Astroid and see if USB icon appears on the top.


Changing Web Address
--------------------

If you have to run multiple Astroid camera under a same network you should change it's host ID. Log in to Astroid using SSH and change host name in raspi-config.

