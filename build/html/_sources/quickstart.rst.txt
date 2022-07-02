.. _quickstart:

Quick Start Guide
=================

Start Astroid
-------------

1. Connect Astroid to a USB power. Make sure to use a stable power source that has at least 5V 3A capacity. 
2. Open up your wifi setup on your mobile device or desktop and find DDS\_DIRECT\_your\_serial. Password is 12345678
3. Open your web browser and type 10.10.10.10 or astroid.local 

.. figure:: /images/ip_address.png
   :alt: IP address
   :align: center

4. You should see the rotating logo soon

.. figure:: /images/rotating_logo.png
   :width: 400
   :alt: Rotating logo
   :align: center

.. admonition:: Note

	The system wake-up usually takes about a minute. If you can't find the SSID in 2 minutes after connecting the power, try to reboot the system by disconnecting and connecting the power. If you can't start the system after multiple trials in this way, your power source might be not enough to stably run Astroid. Please try another power source. For more information, please refers to the manual.
  

Lens Mount
-------------

Astroid Multi can be used in two diffrent ways. If you would like to use the sky recognition feature in **eFinder** and **Dr. Pole**, please mount the provided 5mm lens to the camera body as follow.

.. figure:: /images/lens_mnt.png
   :width: 400
   :alt: Lens mount
   :align: center
   


..
   _This: 사진 바꿀것



eFinder 
-----------

This feature of Astroid completely substitutes the conventional dot finder or finder scope. With the built-in sensor and the basic lens, you can use Astroid as an electronic finder. Astroid's eFinder does not just show you sky image but can tell you what are you looking at and guide you to the sky objects you would like to see.

Follow the procedure below to use eFinder.

1. Mount the holder to your telescope.  

..
   _This: 실제 장착 사진, 마운트 사진

2. Slide Astroid camera into the holder and lock the bolt on the holder using the provided hex key.

..
   _This: 사진


3. Rotate the lens to adjust focus if it is the first time. But the focus is adjusted to the right position when assembled in the factory. Please do this step only when required.


..
   _This: 사진


4. If it is the first time to use or the location you use Astroid is far away from the last location, update the longitude and latitude value under Astro Tools menu. Click the setting |setting_icon| icon to show the menu. 

.. figure:: /images/longlat.png
   :width: 400
   :align: center
   
.. |setting_icon| image:: /images/setting.png
                :scale: 30 %   


If you don't know your longitude and latitude, go to google map and see what is your longitude and latitude. *This manual GPS input will be changed to automatic in the future update.*

.. figure:: /images/gps_google_maps.png
   :alt: GPS location from google maps
   :align: center
   
   


.. list-table:: example longitude and lattitude
   :align: center
   :widths: 25 25 50
   :header-rows: 1
   

   * - Location
     - long
     - lat
   * - Australia Brisbane
     - 152.887277
     - -28.030904 
   * - Korea
     - 127.667991
     - 36.664273
   * - New Zealand
     - 174.807480
     -  -36.866884
   * - Italy milano
     - 9.184879
     - 45.466708 
   * - US Kansas  
     - -98.139525 
     -  38.396799 
   * - Japan
     - 140.002557
     - 35.736418



5. Click the eye button |liveps| to start live sky recognition. 

.. |liveps| image:: /images/liveps.png
                :scale: 30 %


6. Align Astroid to the main telescope lens. To show the alignment joystick, click align icon |dgs_align| on the down side icon bar. See the next section for more details.  
   
.. |dgs_align| image:: /images/dgs_align.png
                :scale: 30 %



7. Touch/click the finder icon |search_icon| on the bottom and search any object you want to find by typing a star ID or name. You can use search key word such as "M1", "ngc3372", "orion". 

.. figure:: /images/finder.png
   :width: 400
   :alt: Finder align 
   :align: center
   
.. |search_icon| image:: /images/search.png
                :scale: 30 %   


8. Touch the location preview icon |preview| to see the location and trail of the star or touch the photo to start the guide mode. The guide mode will tell you which direction you should move your main telescope to see the target start.


.. |preview| image:: /images/btGotoSelectedObject-on.png
                :scale: 70 %   


9. Red target mark is what your main lens is looking at and the green mark is what you need to go. The small arrow around the red target is the direction you should move to.

.. figure:: /images/search_guideline2.png
   :width: 400
   :alt: Guide line
   :align: center

10. Move your mount slowly so that the red target mark and green mark meet

11. When the target star is close to the main scope, a fine tuning target board will appear on the top left corner to assis you with fine movement.



.. figure:: /images/close_target_board.png
   :width: 400
   :alt: Guide line
   :align: center
   
12. If you see the target object in your main telecope's eyepiece, terminate the guide mode by clicking "Finish" button on the left bottom corner.

..
   _This: 사람이 아이피스 보는 사진



.. admonition:: Tips

    Once the sky is recognized, move your mount slowly so that Astroid does not lose the recognized stars. Once it lost the stars, it will take about 2~5 seconds to recover.
    
    
   
eFinder Align
-------------

If you would like to use astroid as a finder along with your main telescope, you have to align Astroid to your main telescope view just like what you do with a conventional finder scope but in a digital way. Follow the procedure below to align Astroid to your main lens.


.. admonition:: Important

    The first alignment is highly recommended to be done in the sunset rather than a dark night. If you have a bright object like a street light around your telescope, the alignment can be done at night too.   

1. Adjust your telescope to put a bright and distinctive object in the center of the eyepiece. Street light or house window light is useful for this. Starlight is not recommended as it is not very distinctive and moving.
2. Press the eye button |liveps| to start sky recognition mode. 
3. Press the setup button |setting_icon| to open the setup panel.

.. |toolbt| image:: /images/bbtSettings-on.png
   :scale: 40 %
   
4. Press the align icon |dgs_align| on the down side icon bar to turn on the align mode.
   
5. Identify the location of the bright object in the image
6. Adjust the joystick to move the red target mark toward the object  


.. figure:: /images/align_star.png
   :alt: Target mark
   :align: center   
   :width: 140
   
   Target mark
   
.. figure:: /images/joystick_img.png
   :alt: Joystick Image
   :align: center   
   :width: 140
   
   Joystick
   
7. Press the align icon |dgs_align| again to terminate the align mode. This will automatically save the current location so that you do not need to do the align next time. 




EAA Stacker
---------------

Electronically Assisted Astronomy (EAA) stacker offers a set of tools that make the live stacking and registration super easy. You can use this feature either for the basic lens, DLSR lens, or telescope. When the stacker is used with the basic lens, it will show the clear shape of the Milkyway which is often very useful to know the location of your interested sky object with respect to the Milkyway. DSLR lens or telescope lens can be mounted on Astroid after removing the basic lens. When EAA stacker is used with these two types of lens, it will give you a much brighter image of the sky object than observing them with your bare eye.

Follow the procedure below to use EAA stacker with a DSLR lens or telescope lens. 

1. Slide the camera into 2 inch scope eyepiece holder. Optionally you can purchase 1.25 inch extension tube and connect it to Astroid to slide it into an eyepiece hole.
2. Set exposure to 0.3 seconds and gain to 150 for fast focusing
3. Adjust your telescope's focus knob and see any star appears on the screen. Finding the right focus could be an extreme job if you do it at night. Do it when it is not too dark and leave a mark around your telescope focuser so that you can easily set the focus to the near position.  
4. Click the stack icon on the bottom right corner to start the image stacking.
5. Stacking will show the best result if F number is low e.g. F2.

Stacking result on Samyang 85mm@F2. 

.. figure:: /images/stacker85mm.png
   :width: 400
   :alt: Stacker 85mm
   :align: center  


To use the EAA stacker with the basic lens, just activate click the stack icon. Adjusting the tone curve and lowering CurveHigh value will make the image even better like the following example.  

.. figure:: /images/stacker5mm_onoff.png
   :width: 400
   :alt: Stacker
   :align: center  

When stacking is enabled in eFinder mode, the stacked image will be aligned to the sky. You can enable eFinder features such as displaying a constellation as shown in the following example.

.. figure:: /images/stacker_const.png
   :width: 400
   :alt: Stacker
   :align: center  

Dr. Pole
---------------

Dr. Pole is a standalone polar alignment assistant tool for EQ mounts. Compared to the existing solution, Dr. Pole does not require the pole star to be within the camera view which makes the polar alignment much easier when you are in the Southern hemisphere or when the pole star is not visible around your place due to a tree or building.  

Follow the procedure below for the polar alignment.

1. Mount the holder to your telescope.  
2. Slide Astroid camera into the holder. If you are using 3D printed version, make sure the back side is firmly hold by the holder.

.. figure:: /images/eq_mnt.png
   :width: 400
   :alt: EQ mount
   :align: center

.. admonition:: Important

    Not like the other products, Astroid can be mounted on the DEC axis or directly on the lens. This gives you more flexibility when the pole star is not visible. You can mount Astroid on the RA axis too. 


3. Rotate the lens to adjust focus if it is the first time. Set exposure to 0.3 seconds and exposure to 150 for fast focusing
4. Click the eye button to start live sky recognition. 
5. Click the telescope icon on the buttom right corner.
6. Move the RA axis of the telescope to the first position (-30 degrees) and wait until the sky is recognized
7. Press the next button and move the RA axis again to 0 degrees and repeat 6,7 for one more time. 
8. Once the axis finder is normally finished, the rotation axis and the SCP or NCP will be displayed on the screen with a guideline.
9. Adjust your mount base according to the guideline


How to Turn Off Astroid
-----------------------

1. Go to System Setting 
2. Press PowerOff button
3. Wait for 10 seconds to be safe
4. Unplug the power

.. admonition:: Important

    If you cut the power without parking, sometimes the SD card is corrupted and you have to recover it to factory setup.
