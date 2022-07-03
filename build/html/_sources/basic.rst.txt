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
                
|ejectmain| Eject USB memory
                
.. |ejectmain| image:: /images/ejectmain.png
                :scale: 60 %
                
|refresh| Refresh screen
                
.. |refresh| image:: /images/refresh.png
                :scale: 60 %
                
|power| Power off
                
.. |power| image:: /images/power.png
                :scale: 60 %



Camera Control Menu
---------------------


.. figure:: /images/menu_cam_setting.png
   :alt: Finder align 
   :align: center



Auto Mode: Auto exposure mode selection. AUTOGAIN fix exposure and only adjust gain

Brightness: Sensor auto exposure level.

Exposure: Sensor exposure time in second.

Gain: Sensor gain 

Image Quality: JPG image quality in percentage. Higher value increase file size and image quality but slower the frame transfer rate.

ZoomMode: Turning this optin will force Astroid to send down sized image in faster frame transfere rate. This option is usuful when focusing.

ZoomSize: Image size in pixel.

Mean Subtraction: Mean subtraction.

Mean Low Cut: Mean subtraction level.

Light Pollution Removal: This will remove gradiant caused by light pollution.

No IR-CUT: Check this option when the IR cut filter is removed

AUTO WB: automatic white balance

PNG Format: Png format image downlaod

TIFF Format: Raw format image download



Astro Tools Menu
---------------------


.. figure:: /images/menu_astro_tools.png
   :alt: Finder align 
   :align: center

Detector: Star detector option

Longitude: Longitude of your location. 

Latitude: Latitude of your location. 

Time Adjust: This can adjust system time to preview the sky at given time

Show Mini Map: Mini image turn on/off

Show Image: Uncheck this option if you only want to see the red circle marker

Show Finder Mark: Uncheck this option if you want to remove the red circle marker

Marker Size: Adjust this slider to set the red circle marker size identical to your main telescope

Show Names: Uncheck this if you want to hide all names

Guide Line: Check this option if you want to see azimuth and elevation guide line in guide mode

Catalogue: This is the star catalogue that automatic nearest star search feature uses.

Min/Max Size: Any DSO larger/smaller than these values will not be automatically searched. Adjust min/max value according to your main telescope's field of view.

Max Distance: Search boundary. Larger value will search wider area.

Min/Max Mag: Any DSO darker/brighter than these values will not be automatically searched. Adjust min/max value according to your preference.

Sort By: When auto search button is clicked in the star list, the found stars will be sorted by this option.

RA(h:m:s), DEC(h:m:s): Custom RA, DEC location for commet and etc. Click "Add to the list" button to add the custom location to the star list.


Timelapse Menu
---------------------


.. figure:: /images/menu_timelapse.png
   :alt: Finder align 
   :align: center

You can select differnt formats for timelapse image saving feature.


System Setting Menu
---------------------


.. figure:: /images/menu_systemsetting.png
   :alt: Finder align 
   :align: center

Support Mode: Checking this to let our support team to remotely dignose your device. Plase speak with our support team first before you use this option.

ID: External wifi's SSID

Pass: External wifi's password

Email: Put your email here to receive the ip address of the device when it connected to the network

Phone: Enter your phone number in international format to receive the IP address.

Get License File: You can download your license file by clicking this button. Downloaded license file can be used to recover your license setting after you recover the system. If you have not sotred this license file download system ID by clicking "Get System ID" and contact us.



Collimation Menu
---------------------


.. figure:: /images/menu_collimation.png
   :alt: Finder align 
   :align: center

Under construction



Setting Up License
-----------------------

Astroid's basic system and apps are protected by HW license keys. For this reason, if you recovered your device from the recovery image provided from the homepage, you have to recover the license as well. This requires to upload the license file to the web interface. The license file can be downloaded by clicking "Get License File" button in the system setting menu. It would be a good pratics to download the license file and store it on your computer once you receive the device. 

To upload the license file go to the system setting menu and click "License Code File" button and select the license file you sotred on your computer.

In case you can't access to the license file, please send us your system ID and serial number. Our staff will send you the license file as soon as possible. 


Also, if you replace Raspberry Pi 4, the original license code would not work. So, if you have any Raspberry Pi related problem please contact us rather than replace the Raspberry Pi yourself.  
 

Hot Pixel Correction
--------------------

The number of hot pixel naturally increses over time. These hot pixels are especially noticeable if you run EAA stacker with tracking option on. Astroid has a built-in hot pixel dector and corrector. But to correct the hot pixel you need to manually activate the hot pixel dector. Please follow the procedure below to detect and correct the hot pixels. 

1. Completly block the sensor using the provided sensor lid. Turn off every light around the room and make the room completely dark. 
2. Go to the camera setting and increase exposure to 1 second and set gain to 150.
3. Go to system menu and adjust hot pixel level. Lower value will pick more hot pixels. 
4. Click hot pixel correction button.
5. Try with the default value and if you still see some week hot pixels, lower the value little bit more until satisfactory.
6. Run EAA stacker and see if hot pixels are disappeared




Writing Images to USB Memory
------------------------------

1. Prepare a DDS USB. Refer to the next section to make a DDS USB
2. Insert the usb to Astroid and see if USB buttons are recognized
3. Click the timelapse button to start recording



.. admonition:: Warnning

    Use high speed USB memorys only. With low speed usb, Astroid will continue to write files to USB even after you finished recording which will drastically increases the chance of file curruption.

.. admonition:: How to eject

    USB must be ejected after eject button is clicked and all the usb related icons are disappeared. Otherwise, the USB will be currupted and you will lost all data in the USB.
    

Making DDS USB
------------------------------

1. Prepare a SanDisk 32GB Ultra Fit or equivalant. High speed USB memory is highly recommanded to prevent any data lost
2. Format the disk with NTFS format and change name to DDS. 
3. Insert the USB to Astroid and see if USB icon appears on the top.


