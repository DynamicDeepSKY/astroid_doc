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

|temp_green| CPU temperature is in a normal range 

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


|lock| Screen lock/unlock

.. |lock| image:: /images/lock.png
                :scale: 60 %


|plus| Zoom in

.. |plus| image:: /images/plus.png
                :scale: 60 %



|minus| Zoom out

.. |minus| image:: /images/minus.png
                :scale: 60 %



|imgrot| Image rotation

.. |imgrot| image:: /images/imgrot.png
                :scale: 60 %



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
                
|autodso_search| Nearest DSO auto display on/off        
                
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



Auto Mode: Auto exposure mode selection. AUTOGAIN fixes exposure and only adjusts the gain.

Brightness: Sensor auto exposure level. Gain or exposure will be automatically adjusted to meet this value.

Exposure: Sensor exposure time in second.

Gain: Sensor gain.

Image Quality: JPG image quality in percentage. A higher value increase file size and image quality but slower the frame transfer rate.

ZoomMode: Turn on this option to receive the cropped image at a faster frame rate. This option is useful when adjusting the focus.

ZoomSize: Image size in pixel.

Mean Subtraction: Check this option to subtract the mean pixel value from the image. This can be used to remove light pollution from the image.

Mean Low Cut: Mean subtraction level.

Light Pollution Removal: This will remove the gradient caused by light pollution. Note that Mean Subtraction above cannot handle light pollution with gradient.

No IR-CUT: Check this option when the IR-CUT filter is removed. This will disable the wrong color correction.

AUTO WB: Automatic white balance. Select this option when IR-CUT filter is removed. The system tries to adjust the white balance without IR-CUT filter.

PNG Format: Png format image download.

TIFF Format: Raw format image download.



Astro Tools Menu
---------------------


.. figure:: /images/menu_astro_tools.png
   :alt: Finder align 
   :align: center

Detector: Star detector method selection.

Longitude: Longitude of your location. 

Latitude: Latitude of your location. 

Time Adjust: This can adjust system time to preview the sky at a given time

Show Mini Map: Mini image turn on/off

Show Image: Uncheck this option if you only want to see the red circle marker

Show Finder Mark: Uncheck this option if you want to remove the red circle marker

Marker Size: Adjust this slider to adjust the red circle marker size identical to your main telescope

Show Names: Uncheck this if you want to hide all names

Guide Line: Check this option if you want to see azimuth and elevation guideline in guide mode

Catalog: This is the star catalog that the automatic nearest star search feature uses.

Min/Max Size: Any DSO larger/smaller than these values will not be automatically searched. Adjust the min/max value according to your main telescope's field of view.

Max Distance: Search boundary. A larger value will search a wider area.

Min/Max Mag: Any DSO darker/brighter than these values will not be automatically searched. Adjust the min/max value according to your preference.

Sort By: When the auto search button is clicked in the star list, the found stars will be sorted by this option.

RA(h:m:s), DEC(h:m:s): Custom RA, DEC location for comet and etc. Click "Add to the list" button to add the custom location to the star list.


Timelapse Menu
---------------------


.. figure:: /images/menu_timelapse.png
   :alt: Finder align 
   :align: center

You can select different formats for the timelapse image saving feature. When you press the timelapse icon |timelapse_small|, the system will write the images in the format you selected above.
                
.. |timelapse_small| image:: /images/timelapse.png
                :scale: 40 %


Tiff and png format will save raw images whereas "Save Annotated" will save the image with additional information such as the direction of the main telescope


System Setting Menu
---------------------


.. figure:: /images/menu_systemsetting.png
   :alt: Finder align 
   :align: center

Support Mode: Check this to let our support team remotely diagnose your device. Please speak with our support team first before you use this option.

ID: External wifi's SSID

Pass: External wifi's password

Email: Put your email here to receive the IP address of the device when it is connected to the network. Note that the email from Astroid is often filtered and delivered to your spam email box. 

.. figure:: /images/wifi_email.png
   :width: 400
   :alt: Wifi notification by email
   :align: center


Phone: Enter your phone number in international format to receive the IP address. The message will be sent only once a day.

.. list-table:: Dialing codes
   :align: center
   :widths: 50 25
   :header-rows: 1   

   * - Region
     - Number
   * - Japan
     - +61
   * - Korea
     - +81
   * - Australia
     - +82     
     
For example, if you connect your device in Australia with the phone number 0401 123 456, you should put it as follows.

.. figure:: /images/wifi_phone.png
   :width: 400
   :alt: Wifi notification by phone
   :align: center


Get License File: You can download your license file by clicking this button. The downloaded license file can be used to recover your license setting after you recover the system. If you have not stored this license file, download the system ID by clicking "Get System ID" and contact us.




Collimation Menu
---------------------


.. figure:: /images/menu_collimation.png
   :alt: Finder align 
   :align: center

Camera: Currently only internal camera is supported

Focus: Focus control for the external auto focus camera

X Offset: To move the circle around x axis

Y Offset: To move the circle around y axis



Setting Up License
-----------------------

Astroid's basic system and apps are protected by HW license keys. For this reason, if you recover your device from the recovery image, you have to recover the license as well. This requires uploading the license file to the web interface. The license file can be downloaded by clicking "Get License File" button in the system setting menu. It would be a good practice to download the license file and store it on your computer once you receive the device.

To upload the license file, go to the system setting menu and click **License Code File** button and select the license file you stored on your computer.

In case you can't access the license file, please send us your system ID and serial number. Our staff will send you the license file as soon as possible. 


Also, if you replace Raspberry Pi 4, the original license code would not work. So, if you have any Raspberry Pi related problems, please contact us rather than replace the Raspberry Pi yourself.  
 

Hot Pixel Correction
--------------------

The number of hot pixels naturally increases over time. These hot pixels are especially noticeable if you run EAA stacker with tracking option on. Astroid has a built-in hot pixel detector and corrector. But to correct the hot pixel you need to manually activate the hot pixel detector. Please, follow the procedure below to detect and correct the hot pixels. 

1. Completly block the sensor using the provided sensor lid. Turn off every light around the room and make the room completely dark. 
2. Go to the camera setting and increase exposure to 1 second and set the gain to 150.
3. Go to the system menu and adjust the hot pixel level. A lower value will pick more hot pixels. 
4. Click the hot pixel correction button.
5. Run EAA stacker and see if hot pixels are disappeared
6. Try with the default value and if you still see some weak hot pixels, lower the value and repeat the above until satisfactory.



Writing Images to USB Memory
------------------------------

1. Prepare a DDS USB. Refer to the next section to make a DDS USB
2. Insert the USB to Astroid and see if USB icon |usbmemory_green| appears on the top status bar
3. Click the timelapse button to start recording

.. |usbmemory_green| image:: /images/usbmemory_green.png
                :scale: 30 %




.. admonition:: Warning

    Use high-speed USB memory only. With low-speed USB, Astroid will continue to write files to USB even after you finished recording which will drastically increase the chance of file corruption.
    

.. admonition:: How to eject

    USB must be ejected after the eject button is clicked and all the USB related icons are disappeared. Otherwise, the USB will be corrupted and you will lose all data in the USB.
    

Making DDS USB
------------------------------

1. Prepare a SanDisk 32GB Ultra Fit or equivalent. High-speed USB memory is highly recommended to prevent any data lost
2. Format the disk with NTFS format and change the name to DDS. 
3. Insert the USB to Astroid and see if the USB icon appears on the top.


